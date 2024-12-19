FROM mcr.microsoft.com/devcontainers/base:jammy

USER vscode

RUN curl -s "https://get.sdkman.io" | bash
RUN chmod +x "$HOME/.sdkman/bin/sdkman-init.sh"
# RUN "$HOME/.sdkman/bin/sdkman-init.sh"
RUN zsh -c "source $HOME/.sdkman/bin/sdkman-init.sh && sdk install java 11.0.17-zulu"
