require "rubygems"
require "rake"

require "choctop"

ChocTop.new do |s|
  # Remote upload target
  s.host     = 'mocra.com'
  # s.base_url   = "http://#{s.host}/projects/jessica"
  s.remote_dir = '/path/to/upload/root/of/app'

  # Custom DMG
  s.background_file = "background.jpg"
  s.app_icon_position = [360, 70]
  s.applications_icon_position = [360, 255]
  s.volume_icon = "jessica_dmg_icon.icns"
end
