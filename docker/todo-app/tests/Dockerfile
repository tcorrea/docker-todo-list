
FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /app/tests/
COPY [".", "."]
ADD ["./node_modules.tar.gz", "/usr/src/app"]
CMD ["npm", "test"]
