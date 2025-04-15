# Gunakan image Ubuntu 22.04 sebagai dasar
FROM ubuntu:22.04
# Perbarui daftar paket dan instal paket-paket dasar yang dibutuhkan
RUN apt-get update && apt-get install -y \ curl \ wget \ build-essential 
    \ git \ libssl3 \ openssl \ && rm -rf /var/lib/apt/lists/*
# (Opsional) Jika Anda ingin meng-install tools tambahan, misalnya 
# Foundry atau Bun: RUN curl -L https://foundry.paradigm.xyz | bash RUN 
# curl -fsSL https://bun.sh/install | bash Set default shell ke bash
SHELL ["/bin/bash", "-c"]
