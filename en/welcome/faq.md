---
refcn: chapter_00/faq
refen: welcome/faq
---

# Frequently Asked Questions (FAQ)

## V2Ray Usage

### How to upgrade V2Ray

* Download latest package, or
* Re-run installation script (Linux only)

### V2Ray Crashes

* If you are using Linux with systemd, you can see panic log using command `journalctl -u v2ray`.
* In general you can run command `v2ray -config=<config-file> -test` to see error information.

### Backward Compatibility

* For configuration file (e.g., JSON), backward compatibility applies to at least one major releases. For example, V2Ray 4.x supports config files from V2Ray 3.x.
* For Protobuf based communication protocols, such as [Api](../configuration/api.md), backward compatibility applies to at least one major releases.
* For binary based commnunication protocols, such as Shadowsocks and VMess, it is always backward compatible when server version is not older than clients. When client version is newer, backward compatibility applies to at least 12 minor releases.

## V2Ray Errors

### Socks: Unknown Socks version: 67

Possible causes

* You are using socks inbound in V2Ray, but your browser is configured to use HTTP proxy.

Solution

* Add a HTTP inbound in V2Ray, and then update your browser proxy settings to use this proxy.

## License of this project

Project V uses the following license.

### V2Ray

Source code and official releases are licensed under MIT license, including the source code and releases in the following repository.

* [v2ray/v2ray-core](https://www.github.com/v2ray/v2ray-core/)
* [v2ray/ext](https://www.github.com/v2ray/ext)

### V2Ray.Com

Official website, [v2ray.com](https://www.v2ray.com/), is licensed under [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

* Including all visible text and pictures on the website.
* Including <a href="https://www.v2ray.com/resources/v2ray_1024.png" target="_blank">Project V logo</a>.
* Including all source code that is used for generating the website, i.e., [v2ray/manual](https://www.github.com/v2ray/manual).

### Screenshot and other files {#screenshots}

All third party files listed below belong to their creator. Whoever creates the file owns the file.

* Including all screenshots of Project V.
* Including all configuration files that are used to run Project V.
* Including all logs generated by Project V during runtime.

### Other content {#other}

All content that are not mentioned above will be licensed case by case.
