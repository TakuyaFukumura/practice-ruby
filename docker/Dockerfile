FROM ruby:3.2.2

RUN apt update &&  \
    apt -y install sqlite3

RUN adduser takuya-fukumura
USER takuya-fukumura

WORKDIR /home/takuya-fukumura

RUN git clone https://github.com/TakuyaFukumura/practice-ruby.git
RUN gem install rails
