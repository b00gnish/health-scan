<h1 align="center" >Ubuntu & Centos Health Scan</h1>
<p align="center" >
	<img src="https://img.shields.io/badge/version-1.1.0-blue.svg?style=for-the-badge" />
	<img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" />
</p>
</br>

About
=============================
This script is setup to scan a centos or ubuntu server to pull some information related to their server resources and web stack.
- Distribution
- Uptime
- CPU
- Load
- numProc
- :80/:443 connections
- Memory
- Disk Space
- I/O
- Nginx
- Varnish
- Redis
- PHP
- Apache
	- KeepAlive
	- KeepAliveTimeout
	- MaxKeepAliveRequests
	- Timeout
	- User
	- Group
	- TraceEnable
	- ServerSignature
	- StartServers
	- ServerLimit
	- MaxRequestWorkers
	- MaxConnectionsPerChild
	- RewriteEngine
	- Listen
	- SSLCipherSuite
	- SSLProtocol
- Mysql
	- datadir
	- default_storage_engine
	- default_tmp_storage_engine
	- have_ssl
	- innodb_buffer_pool_instances
	- innodb_buffer_pool_size
	- innodb_file_per_table
	- innodb_flush_log_at_trx_commit
	- innodb_flush_method
	- innodb_log_buffer_size
	- innodb_log_files_in_group
	- innodb_read_io_threads
	- innodb_write_io_threads
	- join_buffer_size
	- key_buffer_size
	- max_allowed_packet
	- max_connect_errors
	- max_connections
	- max_heap_table_size
	- open_files_limit
	- query_cache_limit
	- query_cache_size
	- query_cache_type
	- read_buffer_size
	- read_rnd_buffer_size
	- skip-innodb_doublewrite
	- sort_buffer_size
	- table_open_cache
	- thread_cache_size
	- tmp_table_size
	- wait_timeout
