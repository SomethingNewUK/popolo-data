require 'jsonlint/rake_task'

JsonLint::RakeTask.new do |t|
  t.paths = %w(
    **/*.json
  )
  t.exclude_paths = %w(
    vendor
  )
end

task :default => :jsonlint