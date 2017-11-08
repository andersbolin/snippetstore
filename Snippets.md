###CODE SNIPPETS###


#####NETWORK SNIPPETS#####

1. #Sets the nw ex: x.x.x.x/32 can be reached through $device_name inteface.
  ip route add $IP_INTERFACE/$NETMASK dev $DEVICE_NAME src $SERVICE_IP table oam
