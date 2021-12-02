[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![CI](https://github.com/grycap/ansible-role-sgx-driver/workflows/CI/badge.svg)](https://github.com/grycap/ansible-role-sgx-driver/actions?query=workflow%3ACI)

Intel SGX Driver Role 
===================

Installs the Intel SGX Driver (https://github.com/intel/linux-sgx-driver).

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows:

	# Version of the driver to install 
	driver_version: "2.14"

Example Playbook
----------------

This an example of how to install the driver:

```yml
  roles:
    - { role: 'grycap.sgx_driver' }
```


Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks



