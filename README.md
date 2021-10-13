# Tomcat with Ansible

Role for installing and configuring a tomcat and jdk dependency.

## Parameters

 * `tomcat_version` - Version of Tomcat
 * `tomcat_download_url` - URL of tar.gz for release
 * `tomcat_download_sha512` - Checksum of tar.gz for release

And ansible-jdk parameters:
 * `jdk_version` - Version of JDK
 * `jdk_download_url` - URL of tar.gz for release
 * `jdk_download_sha256` - Checksum of tar.gz for release

## Testing

Credit: Tested with vagrant image from [@geerlingguy's Ansible for Devops](https://github.com/geerlingguy/ansible-for-devops)

Run the following from the test directory:

### Initial Install
```
vagrant up
```

### Reapply provisioning
```
vagrant provision
```
