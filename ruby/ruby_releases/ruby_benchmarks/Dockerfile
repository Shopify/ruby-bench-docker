FROM rubybench/ruby_releases_base:20170213.1

RUN git clone --verbose --branch master --single-branch https://github.com/shopify/ruby-bench-suite.git

ADD runner runner
RUN chmod 755 runner

CMD /bin/bash -l -c "./runner"
