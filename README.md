- š Hi, Iām @bakhtdogar
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
bakhtdogar/bakhtdogar is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


------------------ Delete code----------------------------
Declare
n number;
v_check;
Begin
v_check:=:main.ptname --(patientname)
if v_Check is null then 
	message('please fill the Patient Name');
	message('please fill the Patient Name');
else
	n := show_alert('info_alert');
	if n = alert_button1 then
		delete from emp where employee_id=:e_id;
		commit;
	else
		-- do nothing 
	end if;
end if;
end;

