# Things Fabric must do to provide the functionality we need for REDCap packaging, deployment, and upgrade.

## Things we should do soon:

* Curate configuration for staging and prod.


## Things we would like Fabric to do but might delay

* make_twilio_features_visible - see redcap\_deployment\_functions.sh
* Read remote database.php to get credentials for DB operations.
* move '    sudo("mkdir -p %s" % env.edoc_path)' out of setup webspace as it is too specific to redcap.
