# pyscript-examples

![GitHub Org's stars](https://img.shields.io/github/stars/FernandoCelmer?label=FernandoCelmer&style=flat-square)
![GitHub last commit](https://img.shields.io/github/FernandoCelmer/pyscript-examples/template?style=flat-square)

---

- **Documentation**: [https://docs.pyscript.net/latest/](https://docs.pyscript.net/latest/)
- **Source Code**: [https://github.com/pyscript/pyscript](https://github.com/pyscript/pyscript)
- **Exemples**: [https://pyscript.net/examples/](https://pyscript.net/examples/)

---

## Introduction

PyScript is a framework that allows users to create rich Python applications in the browser using HTML's interface and the power of Pyodide, WASM, and modern web technologies.


## Run

### Building the Docker image

```bash
docker build --tag nginx/dev --file Dockerfile.nginx .
```

### Starting the Docker container

```bash
docker run -d -t -p 80:80 nginx/dev
```

## Exemples

### Hello world

A static demo of the <py-script> tag

- [https://pyscript.net/examples/hello_world.html](https://pyscript.net/examples/hello_world.html)
- [http://0.0.0.0/examples/hello_world/](http://0.0.0.0/hello_world/)

### Simple clock

A dynamic demo of the <py-script> tag

- [https://pyscript.net/examples/simple_clock.html](https://pyscript.net/examples/simple_clock.html)
- [http://0.0.0.0/examples/simple_clock/](http://0.0.0.0/simple_clock/)

### TODO App

Simple TODO App

- [https://pyscript.net/examples/todo.html](https://pyscript.net/examples/todo.html)
- [http://0.0.0.0/examples/todo/](http://0.0.0.0/todo/)

## Commit Style

- ⚙️ FEATURE
- 📝 PEP8
- 📌 ISSUE
- 🪲 BUG
- 📘 DOCS
- 📦 PyPI
- ❤️️ TEST
- ⬆️ CI/CD
- ⚠️ SECURITY

## License

This project is licensed under the terms of the MIT license.
