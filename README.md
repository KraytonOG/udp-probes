Due to public demand, here is the zmap command to scan with these probes.
Example for ntp monlist;

zmap -p 123 --probe-args=file:ntpmonlist.pkt -o ntpmonlist.txt

You can also add threads to this too by executing -T5 (or whatever threads your server can handle)
