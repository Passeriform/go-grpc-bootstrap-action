# Go gRPC Bootstrap Action

![License](https://img.shields.io/github/license/Passeriform/go-grpc-bootstrap-action)
![Issues](https://img.shields.io/github/issues/Passeriform/go-grpc-bootstrap-action)
![Stars](https://img.shields.io/github/stars/Passeriform/go-grpc-bootstrap-action)

A composite action to setup a Go and gRPC environment with protobuf bindings and optional code generation.

## Usage

```yml
- name: Bootstrap Go and gRPC
  uses: passeriform/go-grpc-bootstrap-action@latest
  with:
    go-version-file: ./go.mod
    protobuf-directory: ./
    generate-protobuf-bindings: true
    generate-code: true
```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a clear description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to open issues or reach out if you encounter any problems or have suggestions for improvements.
