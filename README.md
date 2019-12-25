## Blue Theme Material UI for ERPNext

Custom Theme for ERPNext v12 on the new Desk 2.0

![alt text](https://discuss.erpnext.com/uploads/default/original/3X/c/f/cfb27faec381f31a05a4daadfda1361682af1804.png)

To install bluetheme,

1. bench get-app https://github.com/yrestom/bluetheme.git
2. bench --site (sitename) install-app bluetheme
3. bench clear-cache

For desktop icons to appear,
There are two files, named desktop-erpnext.py and desktop-frappe.py, in the <a href="https://github.com/hashirluv/bluetheme/releases"> releases</a> page. 
1. Rename the file desktop-erpnext.py to desktop.py and replace in frappe-bench/apps/erpnext/erpnext/config folder after taking the backup of the original file.
2. Rename the file desktop-frappe.py to desktop.py and replace in frappe-bench/apps/frappe/frappe/config folder after taking the backup of the original file.


To uninstall bluetheme

1. bench --site (sitename) uninstall-app bluetheme
2. Restore the original desktop.py in erpnext and frappe config folders


** Please check the codes and help me refine it, in case the way i did the changes are not correct.

#### License

GNU General Public License
