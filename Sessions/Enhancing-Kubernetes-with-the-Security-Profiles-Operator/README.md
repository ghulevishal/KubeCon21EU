Kubernetes provides ways for container workloads to leverage Linux security features like seccomp, Apparmor, and SELinux, technologies that allow applications to be bound by security profiles that prevent unexpected and malicious behavior. But crafting and deploying these profiles is a manual process that requires administrators to operate directly on the underlying host and end-users to have knowledge of the security configurations of the hosts.

The Security Profiles Operator is an out-of-tree Kubernetes enhancement that provides cloud-native APIs to manage these profiles.

In this session, Colleen and Sascha will discuss how the Security Profiles Operator has evolved. They demonstrate how the project empowers workload security by making seccomp profiles easier to use inside of Kubernetes. Besides that, they will speak about the future of the project, how it may integrate into Kubernetes and what it means to combine profile-based security features managed from one source of truth.
