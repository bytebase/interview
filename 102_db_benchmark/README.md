# DB Benchmark

This project is to collect the public cloud providers database benchmark and display the benchmark in a web UI.

# Instructions

This project contains 2 parts, one is to collect the benchmark, one is to display the benchmark. We recommend you to first mock the benchmark and finish the UI part. If time permits, you can use [sysbench](https://github.com/akopytov/sysbench) to obtain the real benchmark, this repo contains different oltp\_\*.lua scripts to benchmark different scenarios, you can benchmark one (e.g. oltp_read_write) or multiple scenarios.

# Minimum Requirements

1. A UI to display the benchmark.
   - If you mock the benchmark, we require the UI to show the benchmark for different database engines with different instance types from a single cloud provider. e.g. For AWS RDS MySQL 8.0, a benchmark for db.t3.micro and db.t3.xlarge, same for RDS PostgreSQL 13.0.
   - If you collect the actual benchmark, we only require the UI to show the benchmark for a single database with single instance type from a single cloud provider. e.g. For AWS RDS MySQL 8.0, a benchmark for db.t3.micro.

# Good to have

### Tech Stack

We don't enforce the tech stack in the assignment, but we recommend the tech stack used in our [main product](https://github.com/bytebase/bytebase#-development) since that's the one you will work with after join. So you may try to get a sense beforehand.

1. Frontend - TypeScript, Vue 3, Tailwind CSS.
1. Backend - Go if you have pure backend background. If you have more frontend background, node is perfectly fine. It's also totally fine if your solution doesn't involve backend at all.

### Features

We don't require any additional features. If you have more time, we recommend you to polish those minimum requirements. But if you can't resist the temptation, just go ahead and surprise us.

# Deliverables

Instruction on how to download the code and run locally.
