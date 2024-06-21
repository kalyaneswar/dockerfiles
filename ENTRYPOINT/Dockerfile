FROM almalinux:9

# Test -1
# CMD [ "ping", "-c5", "google.com" ]
# ENTRYPOINT [ "ping", "-c5", "google.com" ]

# Test -2 
# Since Entrypoint can't override we can mix both to use effectively, entrypoin t as fixed and cmd as flexi
CMD [ "google.com" ]
ENTRYPOINT [ "ping", "-c5" ]
