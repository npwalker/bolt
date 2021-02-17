# frozen_string_literal: true

forge "http://forge.puppetlabs.com"

moduledir File.join(File.dirname(__FILE__), 'modules')

# Core modules used by 'apply'
mod 'puppetlabs-service', '1.4.0'
mod 'puppetlabs-puppet_agent', '4.4.0'
mod 'puppetlabs-facts', '1.4.0'

# Core types and providers for Puppet 6
mod 'puppetlabs-augeas_core', '1.1.1'
mod 'puppetlabs-host_core', '1.0.3'
mod 'puppetlabs-scheduled_task', '2.3.1'
mod 'puppetlabs-sshkeys_core', '2.2.0'
mod 'puppetlabs-zfs_core', '1.2.0'
mod 'puppetlabs-cron_core', '1.0.5'
mod 'puppetlabs-mount_core', '1.0.4'
mod 'puppetlabs-selinux_core', '1.0.4'
mod 'puppetlabs-yumrepo_core', '1.0.7'
mod 'puppetlabs-zone_core', '1.0.3'

# Useful additional modules
mod 'puppetlabs-package', '1.4.0'
mod 'puppetlabs-puppet_conf', '0.8.0'
mod 'puppetlabs-python_task_helper', '0.5.0'
mod 'puppetlabs-reboot', '3.2.0'
mod 'puppetlabs-ruby_task_helper', '0.6.0'
mod 'puppetlabs-ruby_plugin_helper', '0.2.0'
mod 'puppetlabs-stdlib', '6.6.0'

# Plugin modules
mod 'puppetlabs-aws_inventory', '0.6.0'
mod 'puppetlabs-azure_inventory', '0.5.0'
mod 'puppetlabs-gcloud_inventory', '0.2.0'
mod 'puppetlabs-http_request', '0.2.1'
mod 'puppetlabs-pkcs7', '0.1.1'
mod 'puppetlabs-secure_env_vars', '0.2.0'
mod 'puppetlabs-terraform', '0.6.1'
mod 'puppetlabs-vault', '0.4.0'
mod 'puppetlabs-yaml', '0.2.0'

# If we don't list these modules explicitly, r10k will purge them
mod 'canary', local: true
mod 'aggregate', local: true
mod 'puppetdb_fact', local: true
mod 'puppet_connect', local: true
