aws-cli-sdb
===========

botocore json file to use simple db with aws cli 

place sdb.json to /path/to/botocore/data/aws .

then you can use it like

$ aws sdb list-domains --output json
{
    "Domains": [
        "ElasticMapReduce-2013-11",
        "hoge"
    ]
}
