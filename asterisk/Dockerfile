FROM asterisk/asterisk:18.11.0

# Copiar configurações personalizadas
COPY config/ /etc/asterisk/

# Expor portas necessárias
EXPOSE 5060/udp 5061/udp 5060/tcp 8088/tcp 8089/tcp 5038 10000-10500/udp

CMD ["asterisk", "-f"]

