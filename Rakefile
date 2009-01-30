require "rubygems"
require "rake"

require "choctop"

ChocTop.new do |s|
  # Remote upload target
  s.host     = 'choctop.rubyforge.org'
  s.base_url   = "http://#{s.host}/jessica_dl"
  s.remote_dir = '/var/www/gforge-projects/choctop/jessica_dl'
  s.host_user = 'nicwilliams'

  # Custom DMG
  s.background_file = "background.jpg"
  s.app_icon_position = [360, 70]
  s.applications_icon_position = [360, 255]
  s.volume_icon = "jessica_dmg_icon.icns"
end
