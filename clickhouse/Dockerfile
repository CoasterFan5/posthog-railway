FROM clickhouse/clickhouse-server:latest

COPY clickhouse_config/zookeeper_config.xml /etc/clickhouse-server/config.d/zookeeper_config.xml
COPY clickhouse_config/cluster_definition.xml /etc/clickhouse-server/config.d/cluster_definition.xml
COPY clickhouse_config/macros.xml /etc/clickhouse-server/config.d/macros.xml
COPY clickhouse_config/listen_config.xml /etc/clickhouse-server/config.d/listen_config.xml



ENTRYPOINT [ "/entrypoint.sh" ]
