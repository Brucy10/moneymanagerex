FROM vcatechnology/linux-mint:18.1
MAINTAINER developers@moneymanagerex.org
RUN apt-get update && \
    apt-get install -y --no-install-recommends \
      cmake build-essential gettext git lsb-release \
      libwebkitgtk-dev libwxgtk3.0-dev libwxgtk-webview3.0-dev \
      automake libtool ccache && \
    apt-get clean
