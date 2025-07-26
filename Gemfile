source "https://rubygems.org"

gem "jekyll"
gem "bundler"
gem "logger"
source "https://rubygems.org"

# Windows için gerekli olan Timezone verileri
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows'ta otomatik sayfa yenileme sorunlarını çözmek için
gem "wdm", ">= 0.1.1", :install_if => Gem.win_platform?