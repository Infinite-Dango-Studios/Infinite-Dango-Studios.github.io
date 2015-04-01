# encoding: utf-8

require "html/proofer"

task :default => [:test]

task :test do
	HTML::Proofer.new("dist/", {
		:href_ignore => [
			"#",
		],
	}).run
end
