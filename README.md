charlie-miller-fuzzer
=====================


Currently, this opens files mentioned in the list file_list. These files must be present in the cwd.
To add any files that you want to fuzz, just append it to the list.


The apps that you want to test are present in the app_list. Depending on what application you want to fuzz, you can change 
that list. The rest of the code is generic and need not be touched. 