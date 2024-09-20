# mp3duration

A Golang package for calculating the duration of an mp3 file. Ported from <https://github.com/kgiannakakis/mp3duration>.

## Usage

```golang
duration, err := mp3duration.Calculate("path/to/demo.mp3")
if err != nil {
    log.Fatal(err)
}
fmt.Printf("Duration %v\n", duration)
```
