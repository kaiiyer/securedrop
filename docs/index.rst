.. SecureDrop documentation master file, created by
   sphinx-quickstart on Tue Oct 13 12:08:52 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to SecureDrop's documentation!
======================================

SecureDrop is an open-source whistleblower submission system that media
organizations can use to securely accept documents from and communicate with
anonymous sources.

.. toctree::
   :caption: User Guides
   :name: userguidetoc
   :maxdepth: 2

   source
   journalist
   admin
   passphrase_best_practices

.. toctree::
   :caption: Install SecureDrop
   :name: installtoc
   :maxdepth: 2

   overview
   glossary
   passphrases
   hardware
   before_you_begin
   set_up_tails
   set_up_svs
   set_up_transfer_and_export_device
   generate_submission_key
   set_up_admin_tails
   network_firewall
   servers
   install
   configure_admin_workstation_post_install
   create_admin_account
   test_the_installation
   onboarding

.. toctree::
   :caption: Deployment Best Practices
   :name: deploymenttoc
   :maxdepth: 2

   deployment_practices
   deployment/landing_page.rst
   deployment/minimum_security_requirements.rst
   deployment/whole_site_changes.rst
   deployment/sample_privacy_policy.rst

.. toctree::
   :caption: Checklists
   :name: checklists
   :maxdepth: 2

   checklists/pre_install_hardware

.. toctree::
   :caption: Topic Guides
   :name: topictoc
   :maxdepth: 2

   getting_the_most_out_of_securedrop
   what_makes_securedrop_unique
   logging
   ossec_alerts
   tails_printing_guide
   https_source_interface
   ssh_over_local_net
   training_schedule
   yubikey_setup
   backup_and_restore
   backup_workstations
   update_tails_usbs
   rebuild_admin
   kernel_troubleshooting
   getting_support
   v3_services

.. toctree::
   :caption: Upgrade SecureDrop
   :name: upgradetoc
   :maxdepth: 2

   upgrade/1.0.0_to_1.1.0.rst
   upgrade/0.14.0_to_1.0.0.rst
   upgrade/xenial_after_april_30.rst

.. toctree::
   :caption: Developer Documentation
   :name: devdocs
   :maxdepth: 2

   development/contributing
   development/setup_development
   development/making_pr
   development/admin_development
   development/updategui_development
   development/client
   development/journalist_api
   development/virtual_environments
   development/virtualizing_tails
   development/upgrade_testing
   development/contributor_guidelines
   development/tips_and_tricks
   development/database_migrations
   development/i18n
   development/l10n
   development/documentation_guidelines
   development/testing_securedrop
   development/testing_application_tests
   development/testing_configuration_tests
   development/testing_continuous_integration
   development/apt_repo
   development/updating_ossec
   development/apparmor_profiles
   development/portable_demo
   development/release_management
   development/dockerbuildmaint
   development/qubes_staging
   development/xenial_support

.. toctree::
  :caption: Threat Model
  :name: threatdoc
  :maxdepth: 2

  threat_model/threat_model.rst
  threat_model/dataflow.rst
  threat_model/mitigations.rst
