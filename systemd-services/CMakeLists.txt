install(FILES suspend-prevent.service DESTINATION etc/systemd/system PERMISSIONS OWNER_READ OWNER_WRITE GROUP_READ WORLD_READ)
install(FILES suspend-prevent-atboot.service DESTINATION etc/systemd/system PERMISSIONS OWNER_READ OWNER_WRITE GROUP_READ WORLD_READ)
