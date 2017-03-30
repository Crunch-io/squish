# squish
A repo for spec files + other packaging files we use

# Package Notes

## RPMS
We do not store tarballs. Make sure that all tarballs (and associated signature
files) are retrieved via network. Use `spectool -g -R <specfile>` to download
remote sources to local. The `.gitignore` file will prevent you from
accidentally adding them.

## NGINX
Taken from EPEL. Added in mod-headers-more mostly cribbed from
http://repo.webtatic.com/yum/el7-testing/SRPMS/RPMS/nginx110-1.10.3-1.w7.src.rpm

