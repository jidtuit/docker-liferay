FROM liferay/liferay-portal
MAINTAINER Jose Ignacío Dominguez Montoya<jose.dominguez@liferay.com>

COPY ./config/portal-ext.properties $LIFERAY_HOME/portal-ext.properties
COPY ./config/portal-setup-wizard.properties $LIFERAY_HOME/portal-setup-wizard.properties

COPY ./config/debug.sh $CATALINA_HOME/bin/debug.sh
COPY ./config/server.xml $CATALINA_HOME/conf/server.xml

EXPOSE 9091 11312

CMD "$CATALINA_HOME/bin/"
ENTRYPOINT ["debug.sh"]

