# Ansible Role - Prometheus

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/role-prometheus?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/role-prometheus/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/role-prometheus?style=for-the-badge)](https://github.com/ursinn-ansible/role-prometheus/blob/main/LICENSE)

Docker Image: https://registry.hub.docker.com/r/prom/prometheus

## Options

| Option | Default Value |
| ---- | ---- |
| role_prometheus_image | docker.io/prom/prometheus:v3.0.0 |
| role_prometheus_container | prometheus |
| role_prometheus_volume | prometheus |
| role_prometheus_network | app-network |
| role_prometheus_tmp_dir | /tmp/ansible-role-prometheus |
| role_prometheus_config_targets | |
| role_prometheus_config_targets_matrix | [] |
| role_prometheus_config_targets_matrix_username | |
| role_prometheus_config_targets_matrix_password | |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/role-prometheus/blob/main/LICENSE) file for the full license text.
