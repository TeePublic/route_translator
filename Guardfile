# frozen_string_literal: true

# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard :test do
  watch(%r{^lib/(.+)\.rb$}) { 'test/route_translator_test.rb' }
  watch(%r{^test/.+_test\.rb$})
  watch('test/test_helper.rb') { 'test' }
end
