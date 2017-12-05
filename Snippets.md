###CODE SNIPPETS###


#####NETWORK SNIPPETS#####

1. #Sets the nw ex: x.x.x.x/32 can be reached through $device_name inteface.
  ip route add $IP_INTERFACE/$NETMASK dev $DEVICE_NAME src $SERVICE_IP table oam

2.  #Network address calc
  NETWORK="$((${gip[0]} & ${msk[0]}))\
           .((${gip[1]} & ${msk[1]}))\
           .((${gip[2]} & ${msk[2]}))\
           .((${gip[3]} & ${msk[3]}))"
           
#########NETWORKSNIPPET##################
SetVirtualRoute(ipnr->ip, ip->mask, ip->recip, ip->ifname);
