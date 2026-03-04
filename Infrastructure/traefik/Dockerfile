FROM traefik:latest

# Cria o direttório e define as permissões corretas
RUN mkdir -p /letsencryptt && \
    touch /letsencryptt/acme.json && \
    chmod 600 /letsencryptt/acme.json

#Define o usuário Traefik (Opcional, mas recomendado para segurança)
USER root

CMD ["traefik"]