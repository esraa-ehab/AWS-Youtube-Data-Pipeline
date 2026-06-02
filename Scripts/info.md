1. Bronze Bucket Name:
yt-pipeline-bronze-bucket-eu-west-3

2. Silver Bucket Name:
yt-pipeline-silver-bucket-eu-west-3

3. Gold Bucket Name:
yt-pipeline-gold-bucket-eu-west-3

4. Scripts Bucket Name:
yt-pipeline-scripts-bucket-eu-west-3
    
5. SNS ARN:
arn:aws:sns:eu-west-3:732592767911:yt-data-pipeline-alerts

6. Glue Raw: 
yt_pipeline_bronze

6. Glue Transformations: 
yt_pipeline_silver

6. Glue Production: 
yt_pipeline_gold

7. --bronze_database            — Bronze Glue catalog database
8. --bronze_table               — raw_statistics
9. --silver_bucket              — Silver S3 bucket
10. --silver_database           — Silver Glue catalog database
11. --silver_table              — clean_statistics table
12. --silver_path               — Silver S3 path prefix

14. --silver_database       — Silver Glue catalog database
15. --gold_bucket           — Gold S3 bucket
16. --gold_database         — Gold Glue catalog database