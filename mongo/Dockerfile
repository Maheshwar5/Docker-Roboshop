FROM mongo:5
# we're using mongo image

# Copying .js (including: catalogue, users etc.) files into docker-entrypoint-initdb.d,
# ... Because whenever you plcae this files, mongodb by default will insert data (catalogue data, etc) into the tables actually.
COPY *.js /docker-entrypoint-initdb.d/

