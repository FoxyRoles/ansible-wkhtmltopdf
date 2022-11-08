# ansible-wkhtmltopdf

Setups Docker.

### Example playbook
```yaml
---
- hosts: myserver
  roles:
    - role: sunfoxcz.wkhtmltopdf
      wkhtmltopdf_version: 0.12.6-1
```

You can find versions on [wkhtmltopdf release page](https://github.com/wkhtmltopdf/packaging/releases).

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
