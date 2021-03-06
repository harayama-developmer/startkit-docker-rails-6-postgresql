source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.6'

gem 'rails', '~> 6.0.1'

gem 'jbuilder', '~> 2.7'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '>= 4.3.2'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 4.0'
# gem 'redis', '~> 4.0'
# gem 'bcrypt', '~> 3.1.7'
# gem 'image_processing', '~> 1.2'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'tzinfo-data'
# Added
gem 'config'
gem 'hamlit-rails'
gem 'rails-i18n', '~> 6.0.0'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  # Added
  gem 'factory_bot_rails'
  gem 'rspec-rails'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
  # Added
  gem 'annotate'            # 現状のスキーマの注釈をコメントとしてファイルの上部や下部に追記してくれる。
  gem 'better_errors'       # エラー画面をデバッグしやすい形に整形してくれる
  gem 'binding_of_caller'   # better-errorsのエラー画面でirbができる
  gem 'bullet'              # 「N+1 問題」を検出してくれる
  gem 'letter_opener_web'   # 送信したメールを確認できる
  gem 'pry-byebug'          # ソースコードにブレークポイントを埋め込んで、所定のポイントでpryを起動
  gem 'pry-rails'           # コンソールをirbからpryに置き換える。
end

group :test do
  gem 'capybara'
  gem 'fuubar'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'webdrivers'
end
