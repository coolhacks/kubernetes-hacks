FROM scratch
MAINTAINER Kelsey Hightower <kelsey.hightower@gmail.com>
COPY kubelet kubelet
VOLUME /etc/os-release /var/lib/docker /var/lib/kubelet /var/run /sys /etc/kubernetes /etc/ssl/certs /rootfs /nsenter /usr /lib64
ENTRYPOINT ["/kubelet"]
