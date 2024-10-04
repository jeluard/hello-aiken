FROM mcr.microsoft.com/devcontainers/rust:1-1-bookworm

USER vscode
RUN curl --proto '=https' --tlsv1.2 -LsSf https://install.aiken-lang.org | sh
RUN $HOME/.aiken/bin/aikup
