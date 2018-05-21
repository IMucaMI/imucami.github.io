#!/usr/bin/env ruby

require 'html-proofer'

task default: %w[test]

task :test do
    options = {
        disable_external: false,
    }
    HTMLProofer.check_directory("./_site").run
end