# ansible-s3

Create Amazon s3 buckets and apply events to them.

vars:
* s3_bucket_state:                    [present|absent] default: present
* s3_bucket_name:                     string
* s3_bucket_policy:                   string json
* s3_bucket_event_id:                 string
* s3_bucket_event_state:              [present|absent] default: present
* s3_buket_event_lambda_function_arn: string
* s3_buket_event_queue_arn:           string
* s3_buket_event_topic_arn:           string
