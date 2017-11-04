FROM parity/parity:v1.8.2

# Parity PoA Torvalds Relay Network
# Torvalds Authority Node: GitToken


# Add Configuration files
WORKDIR /root/parity

# Add Configuration files
ADD config.toml .
ADD chain.json .

WORKDIR /root/parity/keys
COPY ./keys .

EXPOSE 30303 8545 8180 8456 30303/udp
CMD parity
