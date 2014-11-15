FROM mikespokefire/drone-ruby-install:0.4.3

RUN ruby-install ruby 2.1.5 -- --disable-install-rdoc

ENV PATH /opt/rubies/ruby-2.1.5/bin:$PATH
RUN gem install bundler --no-ri --no-rdoc
