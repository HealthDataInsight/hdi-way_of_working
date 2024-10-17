# frozen_string_literal: true

source 'https://rubygems.org'

# TODO: Remove these once gems have been published
gem 'way_of_working', git: 'https://github.com/HealthDataInsight/way_of_working.git', branch: 'feature/v2-wip'

def github_gem(plugin_name)
  gem_name = "way_of_working-#{plugin_name}"
  gem gem_name, git: "https://github.com/HealthDataInsight/#{gem_name}.git", branch: 'feature/v1.0.0'
end

# 'changelog-keepachangelog'
github_gem('code_linting-hdi')
github_gem('code_of_conduct-contributor_covenant')
github_gem('decision_record-madr')
# 'github_audit'
# 'github_audit-cis'
# 'inclusive_language-alex'
# 'pull_request_template-hdi'

# Specify your gem's dependencies in hdi-way_of_working.gemspec
gemspec

gem 'rake', '~> 13.0'

gem 'minitest', '~> 5.16'
