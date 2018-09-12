FROM personlin/geospatial-shiny

MAINTAINER Person Lin (personlin@gmail.com)

# install additional R packages
RUN R -e "install.packages(c('DT', 'gtools', 'doFuture')) \
         & devtools::install_github('personlin/GMPEhaz')"

