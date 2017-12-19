# Ansible role – Munkireport

Ansible role for setting up and configuring munkireport.


## Variables

* **mac\_local\_admin\_username** – Shortname of local admin for ssh (string) [macadmin]

* **munkireport\_allow\_migrations** – Allow database migrations (boolean) [FALSE]

* **munkireport\_apps\_to\_track** – List of apps for MR to track (array) [iTunes, Safari]

* **munkireport\_client\_passphrases** – MR [client passphrase](https://github.com/munkireport/munkireport-php/wiki/Client-passphrase) (array) [secretclientpassphrase]

* **munkireport\_credentials** – MR user credentials (array)

* **munkireport\_debug** – Set debug mode (boolean) [FALSE]

* **munkireport\_disk\_thresholds\_danger** – Storage (GB) remaing danger threshold (int) [25]

* **munkireport\_disk\_thresholds\_warning** – Storage (GB) remaing warning threshold (int) [100]

* **munkireport\_domain\_name** – Domain name (string) [*IPv4 address*]

* **munkireport\_google\_maps\_api\_key** – Google Maps API key for Location Report (string)

* **munkireport\_modules** – Modules to install on clients (array) [*all modules*]

* **munkireport\_roles\_admins** – Munkireport admin users (array)

* **munkireport\_roles\_users** – Munkireport non-admin users (array)

* **munkireport\_site\_name** – Site name (string) [MunkiReport]

* **mysql\_munkireport\_password** – Munkireport database password (string) [mysqlmunkireportpassword]

* **munkireport\_time\_zone** – Time zone (string) [America/Los_Angles]
