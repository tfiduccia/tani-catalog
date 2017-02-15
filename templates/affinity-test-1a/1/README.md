# Affinity Test 1a


### Info:

  This template test two services.  First service has a label that is foo=bar.  The second service has scheduling rule to find host that container with label of foo=bar.  Because of this rule both services should be created on same host.  This is the second version