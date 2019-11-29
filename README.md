sudo apt install protobuf-compiler libprotobuf-dev autotools-dev dh-autoreconf iptables pkg-config dnsmasq-base apache2-bin debhelper libssl-dev ssl-cert libxcb-present-dev libcairo2-dev libpango1.0-dev

cd mahimahi

./autogen.sh

./configure

make

./src/frontend/findcacheable <mahimahi_dir_path>/
