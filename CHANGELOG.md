# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


## Unreleased as of Sprint 87 ending 2018-06-04

### Added
- Add sysprep template support [(#263)](https://github.com/ManageIQ/manageiq-providers-azure/pull/263)
- Add Germany North and Germany West Central regions [(#261)](https://github.com/ManageIQ/manageiq-providers-azure/pull/261)
- Added French and Australian regions fix Southeast Asia description. [(#260)](https://github.com/ManageIQ/manageiq-providers-azure/pull/260)

## Unreleased as of Sprint 84 ending 2018-04-23

### Added
- Azure labels and tag mapping support for a new refresh [(#229)](https://github.com/ManageIQ/manageiq-providers-azure/pull/229)

## Unreleased as of Sprint 82 ending 2018-03-26

### Added
- Optimize API collections [(#220)](https://github.com/ManageIQ/manageiq-providers-azure/pull/220)
- Azure events targeted [(#222)](https://github.com/ManageIQ/manageiq-providers-azure/pull/222)

### Fixed
- Fix case-sensitive events ems_ref parsing [(#225)](https://github.com/ManageIQ/manageiq-providers-azure/pull/225)

## Unreleased as of Sprint 81 ending 2018-03-12

### Added
- Azure graph refresh event target parser [(#219)](https://github.com/ManageIQ/manageiq-providers-azure/pull/219)

### Fixed
- Consolidate Azure refresh workers [(#216)](https://github.com/ManageIQ/manageiq-providers-azure/pull/216)

## Gaprindashvili-2 released 2018-03-06

### Fixed
- Handle possible race conditions for disks, events [(#209)](https://github.com/ManageIQ/manageiq-providers-azure/pull/209)

## Unreleased as of Sprint 80 ending 2018-02-26

### Added
- Added azure_tenant_id to API_ALLOWED_ATTRIBUTES [(#198)](https://github.com/ManageIQ/manageiq-providers-azure/pull/198)

### Fixed
- Allow users to choose public or private IP when provisioning multiple VMs [(#210)](https://github.com/ManageIQ/manageiq-providers-azure/pull/210)

## Unreleased as of Sprint 79 ending 2018-02-12

### Fixed
- Treat securestring case insentive [(#206)](https://github.com/ManageIQ/manageiq-providers-azure/pull/206)

## Gaprindashvili-1 - Released 2018-01-31

### Added
- Handle possibility of arrays for Network Security Groups [(#180)](https://github.com/ManageIQ/manageiq-providers-azure/pull/180)
- Correct and update disk information [(#158)](https://github.com/ManageIQ/manageiq-providers-azure/pull/158)
- SSA Support for Managed Images [(#133)](https://github.com/ManageIQ/manageiq-providers-azure/pull/133)
- Add logging of timings counts and memory usage [(#128)](https://github.com/ManageIQ/manageiq-providers-azure/pull/128)
- Add support for regions in Germany [(#98)](https://github.com/ManageIQ/manageiq-providers-azure/pull/98)
- Changes to wait for snapshot completion. [(#126)](https://github.com/ManageIQ/manageiq-providers-azure/pull/126)
- Wait for SSA Snapshot Success [(#125)](https://github.com/ManageIQ/manageiq-providers-azure/pull/125)
- Snapshot Blob Disks for SSA [(#122)](https://github.com/ManageIQ/manageiq-providers-azure/pull/122)
- Create resource group association for instances and managed images [(#72)](https://github.com/ManageIQ/manageiq-providers-azure/pull/72)
- Refactor discovery code eliminate a warning [(#104)](https://github.com/ManageIQ/manageiq-providers-azure/pull/104)
- Add additional_regions support and add specs for regions [(#103)](https://github.com/ManageIQ/manageiq-providers-azure/pull/103)
- Marketplace image support [(#95)](https://github.com/ManageIQ/manageiq-providers-azure/pull/95)
- Add blacklists for VM username and password when provisioning [(#88)](https://github.com/ManageIQ/manageiq-providers-azure/pull/88)
- Disable reset operation for VMs and add specs [(#81)](https://github.com/ManageIQ/manageiq-providers-azure/pull/81)
- Use a simpler name for network ports [(#80)](https://github.com/ManageIQ/manageiq-providers-azure/pull/80)
- Decrypt client keys in raw connect [(#86)](https://github.com/ManageIQ/manageiq-providers-azure/pull/86)
- Make azure-armrest dependency less pessimistic [(#55)](https://github.com/ManageIQ/manageiq-providers-azure/pull/55)
- Allow for possibility of private IP [(#172)](https://github.com/ManageIQ/manageiq-providers-azure/pull/172)
- Log warning if no provider region is specified [(#191)](https://github.com/ManageIQ/manageiq-providers-azure/pull/191)
- Azure doesn't support discovery [(#193)](Fixes to cleanup agents if AgentCoordinatorWorker is restarted)

### Fixed
- Add a guard when getting power status for a VM [(#178)](https://github.com/ManageIQ/manageiq-providers-azure/pull/178)
- Update VCR cassettes [(#179)](https://github.com/ManageIQ/manageiq-providers-azure/pull/179)
- Added supported_catalog_types [(#185)](https://github.com/ManageIQ/manageiq-providers-azure/pull/185)
- Set api-version explicitly for discovery and regenerate cassettes [(#183)](https://github.com/ManageIQ/manageiq-providers-azure/pull/183)
- Guard against deleted NIC on load balancer [(#181)](https://github.com/ManageIQ/manageiq-providers-azure/pull/181)
- Add the :all flag for metrics collection [(#176)](https://github.com/ManageIQ/manageiq-providers-azure/pull/176)
- Add an Azure STI class for ResourceGroup [(#165)](https://github.com/ManageIQ/manageiq-providers-azure/pull/165)
- Downcase ems_ref for resource groups [(#156)](https://github.com/ManageIQ/manageiq-providers-azure/pull/156)
- Don't assume NIC IP configuration has subnet [(#132)](https://github.com/ManageIQ/manageiq-providers-azure/pull/132)
- Don't collect information externally if marketplace images are specified [(#124)](https://github.com/ManageIQ/manageiq-providers-azure/pull/124)
- Add Snapshot Code for Azure Managed Disks [(#117)](https://github.com/ManageIQ/manageiq-providers-azure/pull/117)
- Updated metric names for Azure metrics [(#114)](https://github.com/ManageIQ/manageiq-providers-azure/pull/114)
- Remove sample orchestration template [(#107)](https://github.com/ManageIQ/manageiq-providers-azure/pull/107)
- Ignore case when gathering data for region  [(#99)](https://github.com/ManageIQ/manageiq-providers-azure/pull/99)
- Fix find_destination_in_vmdb to use insensitive find azure machine name in vmdb [(#93)](https://github.com/ManageIQ/manageiq-providers-azure/pull/93)
- Security Groups array_integer data type [(#91)](https://github.com/ManageIQ/manageiq-providers-azure/pull/91)
- Fix VM password restrictions [(#87)](https://github.com/ManageIQ/manageiq-providers-azure/pull/87)
- Provisioning - First and Last names are not required. [(#73)](https://github.com/ManageIQ/manageiq-providers-azure/pull/73)
- Pass resource group as a string to power operation methods [(#160)](https://github.com/ManageIQ/manageiq-providers-azure/pull/160)
- Smart state Snapshot Managed Disk Name 80 Char Limit [(#157)](https://github.com/ManageIQ/manageiq-providers-azure/pull/157)
- Pass manageiq-smartstate the Resource Group Name not the Object [(#155)](https://github.com/ManageIQ/manageiq-providers-azure/pull/155)
- Fix exception handing for credential validation on raw_connect [(#161)](https://github.com/ManageIQ/manageiq-providers-azure/pull/161)

## Unreleased as of Sprint 78 ending 2018-01-29

### Added
- Migrate model display names from locale/en.yml to plugin [(#200)](https://github.com/ManageIQ/manageiq-providers-azure/pull/200)
- Update api-version string settings [(#186)](https://github.com/ManageIQ/manageiq-providers-azure/pull/186)

### Fixed
- Only create new Public IP if one cannot be found [(#195)](https://github.com/ManageIQ/manageiq-providers-azure/pull/195)

## Unreleased as of Sprint 75 ending 2017-12-11

### Added
- Select only the event fields that we need [(#171)](https://github.com/ManageIQ/manageiq-providers-azure/pull/171)

### Fixed
- Add resourceProviderName to list of collected event fields [(#182)](https://github.com/ManageIQ/manageiq-providers-azure/pull/182)

## Unreleased as of Sprint 72 ending 2017-10-30

### Added
- Pass resource group as a string to the instance delete method [(#148)](https://github.com/ManageIQ/manageiq-providers-azure/pull/148)

### Fixed
- Set the location property of managed disks to ensure disk saving [(#143)](https://github.com/ManageIQ/manageiq-providers-azure/pull/143)
- Always collect all resource groups [(#142)](https://github.com/ManageIQ/manageiq-providers-azure/pull/142)

## Fine-3

### Added
- Refactor service creation lock down api-version strings [(#51)](https://github.com/ManageIQ/manageiq-providers-azure/pull/51)
- Add support for managed images [(#65)](https://github.com/ManageIQ/manageiq-providers-azure/pull/65)

### Fixed
- Upgrade armrest gem to 0.7.3 [(#74)](https://github.com/ManageIQ/manageiq-providers-azure/pull/74)
- Handle possibility of network_port not having private_ip_address [(#85)](https://github.com/ManageIQ/manageiq-providers-azure/pull/85)
- Handle possibility of no orchestration stacks [(#84)](https://github.com/ManageIQ/manageiq-providers-azure/pull/84)

## Fine-1

### Added
- Add backtrace info to verify_credentials failure [(#43)](https://github.com/ManageIQ/manageiq-providers-azure/pull/43)
- Move settings from ManageIQ main repo [(#40)](https://github.com/ManageIQ/manageiq-providers-azure/pull/40)
- Azure deployment refresh enhancement [(#21)](https://github.com/ManageIQ/manageiq-providers-azure/pull/21)
- Associate a floating ip with its load balancer [#17](https://github.com/ManageIQ/manageiq-providers-azure/pull/17)
- Return the Floating IPs available for reuse during instance provisioning [#25](https://github.com/ManageIQ/manageiq-providers-azure/pull/25)
- Support for US Government regions [#28](https://github.com/ManageIQ/manageiq-providers-azure/pull/28)

### Changed
- Update armrest version to 0.7.0 [(#42)](https://github.com/ManageIQ/manageiq-providers-azure/pull/42)
- Delete all resources when deleting an Azure stack [#24](https://github.com/ManageIQ/manageiq-providers-azure/pull/24)

### Fixed
- Ensure managers change zone and provider region with CloudManager [(#47)](https://github.com/ManageIQ/manageiq-providers-azure/pull/47)
- Warn and bail on timeout when collecting metrics [(#44)](https://github.com/ManageIQ/manageiq-providers-azure/pull/44)
- Move require statement into the insights? method [(#38)](https://github.com/ManageIQ/manageiq-providers-azure/pull/38)
- Check for offer attribute when checking for Guest OS [(#37)](https://github.com/ManageIQ/manageiq-providers-azure/pull/37)
- Disable metrics and events in unsupported regions [(#36)](https://github.com/ManageIQ/manageiq-providers-azure/pull/36)

## Initial changelog added
