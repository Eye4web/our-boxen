# This file manages Puppet module dependencies.
#
# It works a lot like Bundler. We provide some core modules by
# default. This ensures at least the ability to construct a basic
# environment.

def github(name, version, options = nil)
  options ||= {}
  options[:repo] ||= "boxen/puppet-#{name}"
  mod name, version, :github_tarball => options[:repo]
end

# Includes many of our custom types and providers, as well as global
# config. Required.

github "boxen",      "3.0.2"

# Core modules for a basic development environment. You can replace
# some/most of these if you want, but it's not recommended.

github "autoconf",   "1.0.0"
github "dnsmasq",    "1.0.0"
github "gcc",        "2.0.1"
github "git",        "1.2.5"
github "homebrew",   "1.4.1"
github "hub",        "1.0.3"
github "inifile",    "1.0.0", :repo => "puppetlabs/puppetlabs-inifile"
github "nginx",      "1.4.2"
#github "nodejs",     "3.2.9"
github "openssl",    "1.0.0"
github "repository", "2.2.0"
github "ruby",       "6.3.4"
github "stdlib",     "4.1.0", :repo => "puppetlabs/puppetlabs-stdlib"
github "sudo",       "1.0.0"
github "xquartz",    "1.1.0"
github "vagrant",    "2.0.14"
github "skype",      "1.0.6"
github "alfred",     "1.1.5"
github "onepassword", "1.0.2"
github "firefox",    "1.1.3"
github "java",       "1.1.0"
github "dropbox",    "1.1.1"
github "chrome",     "1.1.1"
github "zsh",        "1.0.0"
github "phpstorm",   "1.0.3"
github "colloquy",   "1.0.0"
github "googledrive", "1.0.2"
github "google_notifier", "1.0.1"
github "virtualbox",  "1.0.7"

# Optional/custom modules. There are tons available at
# https://github.com/boxen.
