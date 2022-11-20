# Toolbox a CLI (Command Line Interface) Application
This app can check ping to the website and get a response code and check disk usage use in CLI.

# Library use
- [Cobra](https://github.com/spf13/cobra)
- [Disk Usage By ricochet2200](https://github.com/ricochet2200/go-disk-usage)
- [Viper](https://github.com/spf13/viper)

# How To Run
Write this command in your CLI.
## Check All Commands
```go
go run main.go
```

## Ping Command
```go
go run main.go net ping --url [url]
```

Example:

```go
go run main.go net ping --url google.com
```

## Disk Usage Command
```go
go run main.go info diskUsage
```