rails_versions = ['~> 3.2.16', '~> 4.0.2', '~> 4.1.0.beta1']

rails_versions.each do |rails_version|
  appraise "rails#{rails_version.slice(/\d+\.\d+/)}" do
    gem 'rails', rails_version
  end
end
