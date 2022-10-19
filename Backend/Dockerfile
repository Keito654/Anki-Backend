FROM --platform=linux/x86_64 mcr.microsoft.com/dotnet/sdk:6.0

RUN apt update
RUN locale-gen ja_JP.UTF-8
RUN localedef -f UTF-8 -i ja_JP ja_JP
ENV LANG=ja_JP.UTF-8
ENV TZ=Asia/Tokyo

