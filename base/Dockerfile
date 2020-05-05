FROM debian:buster-slim

RUN apt-get update && apt-get install -y --no-install-recommends \
  # Install .NET Core dependencies
  krb5-locales libicu63 libk5crypto3 libkeyutils1 libkrb5-3 libkrb5support0 libssl1.1 \
  # Install VSOnline dependencies
  ca-certificates git git-man less libbsd0 libcurl3-gnutls libedit2 \
  liberror-perl libexpat1 libgdbm-compat4 libgdbm6 libgssapi-krb5-2 \
  libldap-2.4-2 libldap-common libnghttp2-14 libpcre2-8-0 libperl5.28 libpsl5 \
  librtmp1 libsasl2-2 libsasl2-modules libsasl2-modules-db libssh2-1 libx11-6 \
  libx11-data libxau6 libxcb1 libxdmcp6 libxext6 libxmuu1 netbase \
  openssh-client openssl patch perl perl-modules-5.28 publicsuffix wget xauth \
  # Git utilities
  git \
  && rm -rf /var/lib/apt/lists/*
