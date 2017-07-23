require 'jsonlint/rake_task'

JsonLint::RakeTask.new(:jsonlint) do |t|
  t.paths = %w(
    **/*.json
  )
  t.exclude_paths = %w(
    vendor/**/*.json
  )
end

task :default => :jsonlint