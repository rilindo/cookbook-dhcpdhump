dhcpdump Cookbook
=================
Installs dhcpdump, which is a wrapper tool for tcpdump that allows you to view DHCP requests and traffic in a more readable form.

Requirements
------------
Tool is specific to Ubuntu. There is another version of it for CentOS, but you will need access to EPEL. Support for it will be added in the future.


Attributes
----------
* `['dhcpdump']['package_name']` - package name. Defaults to `dhcpdump`.

Usage
-----

Just include `dhcpdump` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[dhcpdump]"
  ]
}
```

Contributing
------------
To contribute

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write you change
4. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Rilindo Foster <rilindo.foster@monzell.com>
