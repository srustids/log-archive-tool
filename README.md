# log-archive-tool
https://roadmap.sh/projects/log-archive-tool

How to Run the Script:

Test with a temporary directory first:
    mkdir -p /tmp/my_test_logs
    echo "Test log entry 1" > /tmp/my_test_logs/app.log
    echo "Another entry" > /tmp/my_test_logs/debug.log
    mkdir -p /tmp/my_test_logs/archive_data
    echo "Archive file 1" > /tmp/my_test_logs/archive_data/data.txt

    ./log-archive-tool.sh /tmp/my_test_logs

requires sudo for /var/log

    sudo ./log-archive-tool.sh /var/log/nginx


