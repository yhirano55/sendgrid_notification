guard :minitest, spring: 'bin/rails test' do
  # with Minitest::Unit
  watch(%r{^test/(.*)_test\.rb$})
  watch(%r{^app/(.*/)?([^/]+)\.rb$}) { |m| "test/#{m[1]}#{m[2]}_test.rb" }
  watch(%r{^test/test_helper\.rb$}) { 'test' }
end
