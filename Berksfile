source "https://supermarket.getchef.com"

metadata

cookbook 'build-essential'
cookbook 'ruby_install', '~> 1.0.4'
cookbook 'libxml2', path: '../libxml2'

group :integration do
  cookbook 'fake', path: 'test/fixtures/cookbooks/fake'
  cookbook 'python'
end