# admin-to-sys-privilege-escalation
This is a very simple privilege escalation technique, from admin to System. This is the same technique PSExec uses.

1) Scan all processes for System token.<br>
2) Copy System token.<br>
3) Adjust Current token.<br>
4) Start process as System.<br>
5) Revert to self.<br>
