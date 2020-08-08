FROM scratch
LABEL maintainer "Seth Vargo <seth@sethvargo.com> (@sethvargo)"
LABEL maintainer "Pradipta Kumar <pradipta.banerjee@gmail.com>"

ADD "https://curl.haxx.se/ca/cacert.pem" "/etc/ssl/certs/ca-certificates.crt"
ADD "./pkg/linux_ppc64le/http-echo" "/"
ENTRYPOINT ["/http-echo"]
