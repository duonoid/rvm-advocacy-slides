!SLIDE code full-screen

    $ tree
.
├── bin
│   └── rvm-install
├── binscripts
│   ├── rvm
│   ├── rvm-auto-ruby
│   ├── rvm-prompt
│   ├── rvm-shell
│   ├── rvmsudo
│   ├── rvm-update-head
│   └── rvm-update-latest
├── config
│   ├── db
│   ├── known
│   └── md5
├── contrib
│   ├── gemset_snapshot
│   ├── hudson
│   │   ├── README.md
│   │   ├── rvmRake-1.0-SNAPSHOT-20100819.hpi
│   │   ├── rvmRuby-1.0-SNAPSHOT-20100819.hpi
│   │   └── rvmRubyMetrics-1.0-SNAPSHOT-20100819.hpi
│   └── install-system-wide
├── docs
│   ├── rebuild.sh
│   └── rvm.txt
├── examples
│   └── rvmrc
├── gemsets
│   ├── default.gems
│   ├── global.gems
│   ├── jruby
│   │   └── global.gems
│   ├── rbx
│   │   └── global.gems
│   ├── ree
│   │   └── 1.8.7
│   │       └── global.gems
│   └── ruby
│       ├── 1.8.7
│       │   └── global.gems
│       ├── 1.9.1
│       │   └── global.gems -> ../1.8.7/global.gems
│       └── 1.9.2
│           └── global.gems -> ../1.8.7/global.gems
├── help
│   ├── alias
│   ├── benchmark
│   ├── cleanup
│   ├── debug
│   ├── disk-usage
│   ├── docs
│   ├── exec
│   ├── fetch
│   ├── gem
│   ├── gemdir
│   ├── gemset
│   ├── implode
│   ├── info
│   ├── install
│   ├── list
│   ├── migrate
│   ├── monitor
│   ├── notes
│   ├── package
│   ├── rake
│   ├── remove
│   ├── repair
│   ├── reset
│   ├── ruby
│   ├── rubygems
│   ├── rvmrc
│   ├── snapshot
│   ├── specs
│   ├── srcdir
│   ├── tests
│   ├── tools
│   ├── uninstall
│   ├── update
│   ├── upgrade
│   ├── use
│   └── wrapper
├── install -> scripts/install
├── lib
│   ├── rvm
│   │   ├── capistrano.rb
│   │   ├── environment
│   │   │   ├── alias.rb
│   │   │   ├── cleanup.rb
│   │   │   ├── configuration.rb
│   │   │   ├── env.rb
│   │   │   ├── gemset.rb
│   │   │   ├── info.rb
│   │   │   ├── list.rb
│   │   │   ├── rubies.rb
│   │   │   ├── sets.rb
│   │   │   ├── tools.rb
│   │   │   ├── utility.rb
│   │   │   └── wrapper.rb
│   │   ├── environment.rb
│   │   ├── errors.rb
│   │   ├── install_command_dumper.rb
│   │   ├── shell
│   │   │   ├── abstract_wrapper.rb
│   │   │   ├── calculate_rvm_path.sh
│   │   │   ├── result.rb
│   │   │   ├── shell_wrapper.sh
│   │   │   ├── single_shot_wrapper.rb
│   │   │   └── utility.rb
│   │   ├── shell.rb
│   │   └── version.rb
│   ├── rvm.rb
│   └── VERSION.yml
├── LICENCE
├── man
│   └── man1
│       ├── rvm.1
│       └── rvm.1.gz
├── patches
│   ├── readline-5.2
│   │   └── shobj-conf.patch
│   ├── ree
│   │   ├── 1.8.7
│   │   │   └── readline-fix.diff -> ../../ruby/1.8.7/readline-fix.diff
│   │   └── fix-irb-completion.diff -> ../ruby/fix-irb-completion.diff
│   └── ruby
│       ├── 1.8.4
│       │   └── railsbench.patch
│       ├── 1.8.5
│       │   ├── backported-ossl-fixes.diff
│       │   └── railsbench.patch
│       ├── 1.8.6
│       │   ├── hs.patch
│       │   ├── mbari.patch
│       │   └── railsbench.patch
│       ├── 1.8.7
│       │   ├── hs.patch
│       │   ├── osx-arch-fix.patch
│       │   ├── p72
│       │   │   ├── mbari-1.patch
│       │   │   ├── mbari-2.patch
│       │   │   ├── mbari-3.patch
│       │   │   ├── mbari-4.patch
│       │   │   ├── mbari-5.patch
│       │   │   ├── mbari-6.patch
│       │   │   ├── mbari7.patch
│       │   │   └── mbari-8b.patch
│       │   ├── railsbench.patch
│       │   └── readline-fix.diff
│       ├── 1.9.1
│       │   └── railsbench.patch
│       ├── 1.9.2
│       │   └── gcdata.patch
│       ├── 1.9.3
│       │   └── gcdata.patch
│       └── fix-irb-completion.diff
├── pkg
│   └── gentoo
│       ├── rvm-0.1.12.ebuild
│       ├── rvm-0.1.13.ebuild
│       ├── rvm-0.1.14.ebuild
│       ├── rvm-0.1.15.ebuild
│       ├── rvm-0.1.16.ebuild
│       ├── rvm-0.1.17.ebuild
│       ├── rvm-0.1.18.ebuild
│       ├── rvm-0.1.19.ebuild
│       ├── rvm-0.1.1.ebuild
│       ├── rvm-0.1.20.ebuild
│       ├── rvm-0.1.21.ebuild
│       ├── rvm-0.1.22.ebuild
│       ├── rvm-0.1.23.ebuild
│       ├── rvm-0.1.24.ebuild
│       ├── rvm-0.1.25.ebuild
│       ├── rvm-0.1.26.ebuild
│       ├── rvm-0.1.27.ebuild
│       ├── rvm-0.1.28.ebuild
│       ├── rvm-0.1.29.ebuild
│       ├── rvm-0.1.2.ebuild
│       ├── rvm-0.1.30.ebuild
│       ├── rvm-0.1.31.ebuild
│       ├── rvm-0.1.32.ebuild
│       ├── rvm-0.1.33.ebuild
│       ├── rvm-0.1.34.ebuild
│       ├── rvm-0.1.35.ebuild
│       ├── rvm-0.1.36.ebuild
│       ├── rvm-0.1.37.ebuild
│       ├── rvm-0.1.38.ebuild
│       ├── rvm-0.1.39.ebuild
│       ├── rvm-0.1.3.ebuild
│       ├── rvm-0.1.40.ebuild
│       ├── rvm-0.1.41.ebuild
│       ├── rvm-0.1.42.ebuild
│       ├── rvm-0.1.43.ebuild
│       ├── rvm-0.1.44.ebuild
│       ├── rvm-0.1.45.ebuild
│       ├── rvm-0.1.46.ebuild
│       ├── rvm-0.1.47.ebuild
│       ├── rvm-0.1.4.ebuild
│       ├── rvm-0.1.5.ebuild
│       ├── rvm-0.1.6.ebuild
│       ├── rvm-1.0.0.ebuild
│       ├── rvm-1.0.10.ebuild
│       ├── rvm-1.0.11.ebuild
│       ├── rvm-1.0.12.ebuild
│       ├── rvm-1.0.13.ebuild
│       ├── rvm-1.0.14.ebuild
│       ├── rvm-1.0.15.ebuild
│       ├── rvm-1.0.16.ebuild
│       ├── rvm-1.0.17.ebuild
│       ├── rvm-1.0.18.ebuild
│       ├── rvm-1.0.19.ebuild
│       ├── rvm-1.0.1.ebuild
│       ├── rvm-1.0.20.ebuild
│       ├── rvm-1.0.21.ebuild
│       ├── rvm-1.0.22.ebuild
│       ├── rvm-1.0.23.ebuild
│       ├── rvm-1.0.2.ebuild
│       ├── rvm-1.0.3.ebuild
│       ├── rvm-1.0.4.ebuild
│       ├── rvm-1.0.5.ebuild
│       ├── rvm-1.0.6.ebuild
│       ├── rvm-1.0.7.ebuild
│       ├── rvm-1.0.8.ebuild
│       ├── rvm-1.0.9.ebuild
│       ├── rvm-1.1.0.ebuild
│       ├── rvm-99999.ebuild
│       └── rvm.ebuild.template
├── Rakefile
├── README
├── scripts
│   ├── alias
│   ├── aliases
│   ├── array
│   ├── base
│   ├── cd
│   ├── cleanup
│   ├── cli
│   ├── color
│   ├── completion
│   ├── db
│   ├── default
│   ├── disk-usage
│   ├── docs
│   ├── env
│   ├── environment-convertor
│   ├── fetch
│   ├── gemsets
│   ├── get
│   ├── hash
│   ├── help
│   ├── hook
│   ├── info
│   ├── initialize
│   ├── install
│   ├── irbrc
│   ├── irbrc.rb
│   ├── list
│   ├── log
│   ├── maglev
│   ├── manage
│   ├── match
│   ├── md5
│   ├── migrate
│   ├── monitor
│   ├── notes
│   ├── override_gem
│   ├── package
│   ├── patches
│   ├── patchsets
│   ├── repair
│   ├── rubygems
│   ├── rvm
│   ├── rvm-install -> ./install
│   ├── selector
│   ├── set
│   ├── snapshot
│   ├── tools
│   ├── update -> ./install
│   ├── upgrade
│   ├── utility
│   ├── version
│   ├── wrapper
│   └── zsh
│       └── Completion
│           └── _rvm
├── test
│   ├── btu
│   ├── integration
│   │   ├── rvm_gemsets
│   │   ├── rvm_install
│   │   ├── rvm_reload
│   │   ├── rvm_update
│   │   └── rvm_update_head
│   ├── rubies
│   │   ├── jruby-1.3.1
│   │   ├── jruby-1.4.0RC3
│   │   ├── macruby-0.5
│   │   ├── rbx-head
│   │   ├── ree-1.8.6-20090610
│   │   ├── ree-1.8.6-head
│   │   ├── ree-1.8.7-2009.10
│   │   ├── ree-1.8.7-head
│   │   ├── ruby-1.8.5-p231
│   │   ├── ruby-1.8.5-tv1_8_5
│   │   ├── ruby-1.8.6-p383
│   │   ├── ruby-1.8.7-p174
│   │   ├── ruby-1.9.1-head
│   │   ├── ruby-1.9.1-p243
│   │   ├── ruby-1.9.1-r25443
│   │   └── ruby-1.9.2-preview1
│   ├── setup
│   ├── suite
│   └── unit
│       ├── cli_test
│       ├── db_test
│       ├── gemdir_test
│       ├── gemset_test
│       ├── rvm-prompt_test
│       ├── selector_test
│       ├── use_test
│       └── utility_test
└── VERSION.yml -> lib/VERSION.yml

45 directories, 276 files
