Pure Go SMART Library
=====================

This is a pure Go implementation of SMART (Self-Monitoring, Analysis and
Reporting Technology), the monitoring system included in most HDDs and SSDs.

This project is a work in progress, in the early stages of development. The API
is highly likely to change during development.

A simple example of how to use the library is included in the `cmd/smartctl`
directory.

References
----------
* http://www.t10.org/ftp/t10/document.04/04-262r8.pdf
* http://www.t13.org/documents/UploadedDocuments/docs2005/e05148r0-acs-smartattributesannex.pdf
* http://www.t13.org/documents/UploadedDocuments/docs2008/D1699r6a-ATA8-ACS.pdf
* http://www.t13.org/documents/UploadedDocuments/docs2009/d2015r2-ATAATAPI_Command_set_-_2_ACS-2.pdf
* http://www.t13.org/documents/UploadedDocuments/docs2013/d2161r5-ATAATAPI_Command_Set_-_3.pdf
* http://www.t13.org/documents/UploadedDocuments/docs2016/di529r14-ATAATAPI_Command_Set_-_4.pdf
* http://www.nvmexpress.org/wp-content/uploads/NVM_Express_Revision_1.3.pdf
* And many more listed in https://en.wikipedia.org/wiki/S.M.A.R.T.#References

---
# 更新说明
1. megaraid/megaraid.go添加了`GetHostNumDeviceID`
2. megaraid/megaraid.go添加了`OpenMegasasIoctlMegaSmart`
