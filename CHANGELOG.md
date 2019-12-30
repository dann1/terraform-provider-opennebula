## 0.1.1 (Unreleased)

ENHANCEMENTS:
* all resources: use Goca dynamic templates to build entitiies
* resource/opennebula_virtual_machine: keep context from template, then override redefined pairs

BUG FIXES:
* resource/opennebula_virtual_machine: Start VM on Hold [GH-1]
* resource/opennbula_virtual_machine: Attach nic or disk in the declared order [GH-5]
* all ressources: Fix changes detected on update while parameters are not set [GH-2]
* resource/opennebula_virtual_network: Fix setting of cluster id on Virtual Network Creation [GH-6]

DEPRECATION:
* resource/opennebula_virtual_machine: Remove `instance` parameter as it is redundant with `name`

## 0.1.0 (November 25, 2019)

NOTES:
* First implementation of the provider
* Basic Tests + CI + Coverage


FEATURES:
* **New Data Source**: `opennebula_group`: First implementation
* **New Data Source**: `opennebula_image`: First implementation
* **New Data Source**: `opennebula_security_group`: First implementation
* **New Data Source**: `opennebula_template`: First implementation
* **New Data Source**: `opennebula_virtual_data_center`: First implementation
* **New Data Source**: `opennebula_virtual_network`: First implementation
* **New Resource**: `opennebula_group`: First implementation ([onegroup](https://docs.opennebula.org/5.8/integration/system_interfaces/api.html#onegroup))
* **New Resource**: `opennebula_image`: First implementation ([oneimage](https://docs.opennebula.org/5.8/integration/system_interfaces/api.html#oneimage))
* **New Resource**: `opennebula_security_group`: First implementation ([onesecgroup](https://docs.opennebula.org/5.8/integration/system_interfaces/api.html#onesecgroup))
* **New Resource**: `opennebula_template`: First implementation ([onetemplate](https://docs.opennebula.org/5.8/integration/system_interfaces/api.html#onetemplate))
* **New Resource**: `opennebula_virtual_data_center`: First implementation ([onevdc](https://docs.opennebula.org/5.8/integration/system_interfaces/api.html#onevdc))
* **New Resource**: `opennebula_virtual_machine`: First implementation ([onevm](https://docs.opennebula.org/5.8/integration/system_interfaces/api.html#onevm))
* **New Resource**: `opennebula_virtual_network`: First implementation ([onevnet](https://docs.opennebula.org/5.8/integration/system_interfaces/api.html#onevnet))
