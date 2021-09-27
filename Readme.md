To install monitoring enter command:
curl -s https://raw.githubusercontent.com/rustamkakar/helpers-monitoring-/main/monitor.sh | bash
When need a custom OWNER or HOSTNAME on dashboards:
export OWNER=new_custom_owner
export NODENAME=new_custom_nodename
After install general monitoring:
To install substate monitoring enter command:
curl -s https://raw.githubusercontent.com/rustamkakar/helpers-monitoring-/main/monitor_add_substrate.sh | bash
To install casper monitoring enter command:
curl -s https://raw.githubusercontent.com/rustamkakar/helpers-monitoring-/main/monitor_add_casper.sh | bash
To install cosmos monitoring enter command:
curl -s https://raw.githubusercontent.com/rustamkakar/helpers-monitoring-/main/monitor_add_cosmos.sh | bash
