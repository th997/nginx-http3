# nginx

## Features

- Based on latest NGINX mainline version
- QUIC support, powered by [nginx-quic](https://quic.nginx.org/)
- Brotli support, powered by [ngx_brotli](https://github.com/google/ngx_brotli)
- Headers More support, powered by [ngx_headers_more](https://github.com/openresty/headers-more-nginx-module)
- OCSP stapling support, powered by [this patch](https://github.com/kn007/patch/blob/master/Enable_BoringSSL_OCSP.patch)
- Zstandard support, powered by [zstd-nginx-module](https://github.com/tokers/zstd-nginx-module)
- Use [BoringSSL](https://github.com/google/boringssl), [Cloudflare's zlib](https://github.com/cloudflare/zlib), [jemalloc](https://github.com/jemalloc/jemalloc) and [PCRE2](https://github.com/PCRE2Project/pcre2)
- Use OpenSSL's hash functions instead of NGINX's, powered by [this patch](https://github.com/kn007/patch/blob/master/use_openssl_md5_sha1.patch)