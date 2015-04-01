# encoding: utf-8

require "html/proofer"

task :default => [:test]

task :test do
	HTML::Proofer.new("_site/", {
		:href_ignore => [
			"#",
		],
		:verbose => true,
		:check_favicon => true,
	}).run
end
