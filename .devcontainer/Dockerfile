FROM public.ecr.aws/docker/library/golang:1.25

# Node.jsのインストール
RUN curl -fsSL https://deb.nodesource.com/setup_24.x | bash - \
    && apt-get install -y nodejs

RUN npm install -g @typespec/compiler

RUN go install github.com/go-delve/delve/cmd/dlv@latest