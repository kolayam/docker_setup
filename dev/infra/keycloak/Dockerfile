FROM youweisoft/keycloak:3.4.3-1

USER jboss
COPY ./themes/ $JBOSS_HOME/themes/

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
