FROM nginx:alpine
LABEL org.opencontainers.image.source=https://github.com/Aleisgar/ci-cd-codelab.git
COPY dist /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
