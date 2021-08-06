## edit data in se16n
1. /h enter
1. start se16n
1. set values in structure `gd`
1. `gd-edit = 'X'`
1. `gd-sapedit = 'X'`
1. enjoy!


## logging tcodes
* su53 - authority check errors
* st22 - dump
* slg1 - all error logs
* /iwfnd/error_log - gateway errors


## odata service url params
* `sap-ui-debug=true`  trace request


## odata server annotations path

### segw service name: `SERVICE_NAME_SRV`
path: /sap/opu/odata/IWFND/CATALOGSERVICE;v=2/Annotations(TechnicalName='`SERVICE_NAME_ANNO_MDL`',Version='0001')/$value

### Restful App. Progr. Model service name: `SERVICE_NAME`
path: /sap/opu/odata/IWFND/CATALOGSERVICE;v=2/Annotations(TechnicalName='`SERVICE_NAME_VAN`',Version='0001')/$value