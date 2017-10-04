forge "https://forgeapi.puppetlabs.com"

# Foreman 1.15
# Dependencies
mod 'puppetlabs/mysql',         '3.10.0'
mod 'puppetlabs/postgresql',    '4.9.0'
mod 'puppetlabs/puppetdb',      '5.1.2'
mod 'theforeman/dhcp',          '3.1.0'
mod 'theforeman/dns',           '4.1.0'
mod 'theforeman/git',           '2.0.0'
mod 'theforeman/tftp',          '2.0.0'

# Top-level modules
mod 'theforeman/foreman',       '7.2.0'
mod 'theforeman/foreman_proxy', '5.1.0'
mod 'theforeman/puppet',        '7.1.1'
### END Foreman 1.15/

# Sub Dependent Modules - Obtained versions from:
#   puppet module list --modulepath /usr/share/foreman-installer/modules
mod 'puppet-extlib', '1.1.0'
mod 'puppet-staging', '2.2.0'
mod 'puppetlabs-apache', '1.11.0'
mod 'puppetlabs-apt', '2.3.0'
mod 'puppetlabs-concat', '2.2.0'
mod 'puppetlabs-firewall', '1.8.2'
mod 'puppetlabs-inifile', '1.6.0'
mod 'puppetlabs-stdlib', '4.16.0'
mod 'puppetlabs-xinetd', '1.5.0' # NOT LATEST - 2.0.0 giving us errors

# Additional Foreman (Puppet) Needs
mod 'puppet-hiera', '3.0.0'
mod 'puppetlabs-puppetserver_gem', '1.0.0'

# The rest that were here before
mod 'puppetlabs-transition', '0.1.1'
mod 'puppetlabs-ruby', '0.6.0'
mod 'puppetlabs-lvm', '0.9.0'
mod 'pcfens-ca_cert', '1.6.1'
mod 'thias-sysctl', '1.0.6'
mod 'thias/fooacl', '1.0.1'
mod 'evenup/redis', '1.3.1'
mod 'echoes/monit', '0.4.0'

# Added for host_railsapp
mod 'puppet/letsencrypt', '1.1.0'
mod 'petems-swap_file', '3.1.4'
mod 'maestrodev/rvm', '1.13.1'
mod 'golja-gnupg', '1.2.3'

# Added for gitlab
mod 'vshn-gitlab', '1.14.0'

# Added for pulp
mod 'stahnma-epel', '1.2.2'

# Added for cloudwatch
mod 'kemra102-cloudwatchlogs', '2.3.1'

## This stuff was inherited

mod 'r10k',
  :git => 'https://github.com/voxpupuli/puppet-r10k.git',
  :ref => 'v6.0.0'

mod 'noop',
  :git => 'https://github.com/trlinkin/trlinkin-noop.git',
  :ref => '0.1.0'

mod 'face-bucket',
  :git => 'https://github.com/dhgwilliam/puppet-face-bucket.git',
  :ref => '0.3.0'

mod 'sudo',
  :git => 'https://github.com/saz/puppet-sudo.git',
  :ref => 'v4.1.0'

mod 'logrotate',
  :git => 'https://github.com/yo61/puppet-logrotate.git',
  :ref => 'v1.4.0'

mod 'nfs',
  :git => 'https://github.com/derdanne/puppet-nfs.git',
  :ref => '2.0.3'

mod 'exports',
  :git => 'https://github.com/acidprime/exports.git',
  :ref => 'v0.0.6'

mod 'ntp',
  :git => 'https://github.com/puppetlabs/puppetlabs-ntp.git',
  :ref => '6.0.0'

mod 'vcsrepo',
  :git => 'https://github.com/puppetlabs/puppetlabs-vcsrepo.git',
  :ref => '1.5.0'

mod 'puppet_agent',
  :git => 'https://github.com/puppetlabs/puppetlabs-puppet_agent.git',
  :ref => '1.3.2'

mod 'gms',
  :git => 'https://github.com/abrader/abrader-gms.git',
  :ref => 'v1.0.3'

mod 'squid3',
  :git => 'https://github.com/thias/puppet-squid3.git',
  :ref => '1.0.2'

mod 'qpid',
  :git => 'https://github.com/katello/puppet-qpid.git',
  :ref => '2.1.0'

mod 'mongodb',
  :git => 'https://github.com/puppetlabs/puppetlabs-mongodb.git',
  :ref => '0.17.0'

mod 'pulp',
  :git => 'https://github.com/Katello/puppet-pulp.git',
  :ref => 'bb68da3' # Post 4.3.0
#  :ref => '4.3.0'

mod 'systemd',
  :git => 'https://github.com/camptocamp/puppet-systemd.git',
  :ref => '0.4.0'


# Forked from dbailey/openvpn_as (for safe keeping)
mod 'openvpn_as',
  :git => 'https://github.com/LarkIT/puppet-openvpn_as.git',
  :ref => 'a202231'

#mod 'host_railsapp',
#    :git => 'git@mbi-gitlab-01.utmb.lan:/puppet/host_railsapp.git',
#    :ref => 'mbi'

mod 'selinux',
   :git => 'https://github.com/LarkIT/puppet-selinux.git',
   :ref => 'larkit'

mod 'shibboleth',
    :git => 'https://github.com/LarkIT/puppet-shibboleth.git',
    :ref => 'testshib' # no release yet

mod 'role',
    :git => 'https://github.com/nfosdick/role.git',
    :ref => 'master'

mod 'profile',
    :git => 'https://github.com/nfosdick/profile.git',
    :ref => 'master'
