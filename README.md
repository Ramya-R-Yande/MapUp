 Instead of using the given Execution "python3 process1.py --to_process /output/process2 --output_dir /output/process1" I have changed python3 to python to all the three process, as shown- "python process1.py --to_process /test/test.parquet --output_dir /output/process1".
 python process2.py --to_process /output/process1 --output_dir /output/process2
 python3 process3.py --to_process /output/process2 --output_dir /output/process3
