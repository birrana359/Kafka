source "https://supermarket.chef.io"

metadata

group :test do
  # Kafka requires zookeeper to run so our tests need this to work
  cookbook "apache_zookeeper"
  cookbook "curl" # Needed by serverspec tests
end
