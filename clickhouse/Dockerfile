FROM clickhouse/clickhouse-server:latest

COPY clickhouse_config/config.xml /etc/clickhouse-server/config.d/config.xml
COPY clickhouse_config/zookeeper_config.xml /etc/clickhouse-server/config.d/zookeeper_config.xml
COPY clickhouse_config/posthog_config.xml /etc/clickhouse-server/config.d/posthog_config.xml
COPY clickhouse_config/user_defined_functions.xml /etc/clickhouse-server/user_defined_functions.xml




ENTRYPOINT [ "/entrypoint.sh" ]
