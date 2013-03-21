desc 'test existing file'
task :checkfile, :fullpath_to_filename,  do |t, args|
if File.exists?(args[:fullpath_to_filename])
  puts "file exists"
else
  puts "file doesn't exist"
end

