![Echo with Nanobox](https://guides.nanobox.io/assets/quickstart-icons/echo.png)

# Echo from scratch

Run a Echo app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>

## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-echo.git

# cd into the echo app
cd nanobox-echo
```

## Run the app

```bash
# Add a convenient way to access your app from a browser
nanobox dns add local echo.dev

# Run Echo as you would normally, with Nanobox
nanobox run go run server.go
```

## Check it out

Visit your app at <a href="http://echo.dev:1323" target="\_blank">echo.dev:1323</a>

## Explore
With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where golang is installed,
go version

# git is installed,
git --version

# and your code is mounted
ls
```

## Now What?
For more details about running Echo apps with nanobox visit [guides.nanobox.io/golang/echo/](https://guides.nanobox.io/golang/echo/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
