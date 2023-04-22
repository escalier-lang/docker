FROM rust:1.69

# Install nodejs
RUN apt-get update && apt-get install -y \
    nodejs \
    npm

# Install yarn
RUN npm install -g yarn

# Install grcov
RUN cargo install --force grcov

# Install llvm-tools-preview
RUN rustup component add llvm-tools-preview
