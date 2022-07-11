FROM mjgargani/puppeteer:trybe1.0
EXPOSE 3000
WORKDIR /test
ADD node_modules.tar.gz .
COPY . .
CMD [ "npm", "test" ]
