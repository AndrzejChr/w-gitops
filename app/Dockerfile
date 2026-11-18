FROM harbor.vcf.atd.lab/dockerhub/library/nginx:1.27
ARG VERSION=dev
COPY index.html /usr/share/nginx/html/index.html
RUN sed -i "s/__VERSION__/${VERSION}/g" /usr/share/nginx/html/index.html
