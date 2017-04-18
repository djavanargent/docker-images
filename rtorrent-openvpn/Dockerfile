FROM binhex/arch-openvpn
LABEL org.freenas.interactive="false"                             \
      org.freenas.version="0.2" 						\
      org.freenas.capabilities-add="NET_ADMIN"                      \
      org.freenas.upgradeable="true" 					\
      org.freenas.expose-ports-at-host="true" 				\
      org.freenas.privileged="true"                               \
      org.freenas.autostart="true" 					      \
      org.freenas.web-ui-protocol="http" 				      \
      org.freenas.web-ui-port="9080" 					\
      org.freenas.web-ui-path="" 					      \
      org.freenas.port-mappings="9091:9091/tcp,9443:9443/tcp,8118:8118/tcp,3000:3000/tcp" \
      org.freenas.volumes="[						      \
          {							                  \
              \"name\": \"/config\",					\
              \"descr\": \"config storage space\"			\
          },                                                      \
          {							                  \
              \"name\": \"/data\",					      \
              \"descr\": \"download location\"			      \
          },							            \
          {							                  \
              \"name\": \"/etc/localtime\",					\
              \"descr\": \"Localtime Setting\"			      \
               \"readonly\": \"true\"                                    \
          },                                                      \
      ]" 								            \
      org.freenas.settings="[ 					      \
          {							                  \
              \"env\": \"VPN_ENABLED\",					      \
              \"descr\": \"Is VPN Enabled\",		      \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"VPN_USER\",			      \
              \"descr\": \"USERNAME\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"VPN_PASS\",				\
              \"descr\": \"PASSWORD\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"VPN_REMOTE\",				\
              \"descr\": \"REMOTE\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"VPN_PORT\",				\
              \"descr\": \"PORT\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"VPN_PROTOCOL\",				\
              \"descr\": \"PROTOCOL\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"VPN_DEVICE_TYPE\",				\
              \"descr\": \"DEVICE TYPE\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"VPN_PROV\",				\
              \"descr\": \"Provider\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"VPN_OPTIONS\",				\
              \"descr\": \"Additional OpenVPN cli options\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"STRONG_CERTS\",				\
              \"descr\": \"STRONG_CERTS\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"ENABLE_PRIVOXY\",				\
              \"descr\": \"Privoxy\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"ENABLE_FLOOD\",				\
              \"descr\": \"Flood UI\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"LAN_NETWORK\",			            \
              \"descr\": \"IP/mask[,IP/mask]\",	                  \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"NAME_SERVERS\",				\
              \"descr\": \"Name Server IPs\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"DEBUG\",				\
              \"descr\": \"DEBUG\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"PHP_TZ\",				\
              \"descr\": \"PHP Yimezone\",			            \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"UMASK\",			            \
              \"descr\": \"Umask for created files\",	                  \
              \"optional\": true				            \
          },							            \
          {							                  \
              \"env\": \"PUID\",				            \
              \"descr\": \"UserID\",			            \
              \"optional\": true				            \
          },                                                      \
          {							                  \
              \"env\": \"PGID\",				            \
              \"descr\": \"GroupID\",		                  \
              \"optional\": true				            \
          } 							            \
      ]"
