Description
Welcome to new way of software delivery with Docker! We are excited to provide you a technology preview of ALM Octane ( public beta) for on premise consumption. This is a technology preview of Dockerized container of ALM Octane.

NOTE: This is meant for staging and sandbox environments ONLY.

The docker Repository is: https://hub.docker.com/r/lifecyclemanagement/octane/

For Questions or Feedback, send us an email: shimon.cherny@microfocus.com.



As Docker images are used for trying out new features, we provide four channels for ALM Octane on Docker. By default, Docker will pull the “latest” – or no tag – release which is always the latest stable release. We also provide more bleeding-edge releases. There are four release channels: ·

Onprem - our latest On Premises (GA) release. This version was thoroughly tested for on premises usage.
Latest / Stable – Found under the “latest” tag (or no tag), it provides the latest stable release. This version was thoroughly tested and is what we use in our SaaS production. You should use this channel if you’re not sure what to use.
Beta – a version that was well tested but may still contain several known issues. This version is a good compromise between getting the latest features and getting a relatively stable version.
Alpha – a version that is released as soon as basic integration tests are done. This version may contain serious issues and is not considered stable but it generally works. Only use when you need the absolute latest.
To pull a different channel, use Docker tags. Use the following commands to pull the different versions:

Onprem: lifecyclemanagement/octane:onprem
Stable: lifecyclemanagement/octane
Latest beta: lifecyclemanagement/octane:beta
Latest alpha: lifecyclemanagement/octane:alpha We also provide tags for each version we release.
For a complete list of all tags available, see: https://hub.docker.com/r/lifecyclemanagement/octane/tags/

Login details:
http://localhost:8080
username: sa@nga
password: OctaneIsTheBest1!
