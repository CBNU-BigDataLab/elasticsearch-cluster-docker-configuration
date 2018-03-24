# https://github.com/elastic/elasticsearch-docker
FROM docker.elastic.co/elasticsearch/elasticsearch:6.1.1

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
RUN elasticsearch-plugin install https://github.com/open-korean-text/elasticsearch-analysis-openkoreantext/releases/download/6.1.1/elasticsearch-analysis-openkoreantext-6.1.1.2-plugin.zip
