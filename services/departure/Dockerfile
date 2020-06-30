FROM ruby:2.5-alpine

RUN mkdir /departure
WORKDIR /departure

ADD Gemfile /departure/Gemfile
ADD Gemfile.lock /departure/Gemfile.lock
RUN bundle install
ADD . /departure