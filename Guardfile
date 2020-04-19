guard 'font-prep' do
  watch(%r{ENV['HOME']/Downloads/.+\.zip})

  callback(:run_on_additions) { puts 'new zipfile found!' }
end
