#
# The command below, will be use to create an ISO image with the content of that folder.
#

#Linux
mkisofs -J -l -R -V "Label CD" -iso-level 4 -o Autounattend.iso .
