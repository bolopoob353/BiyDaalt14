# Бие даалт 14 — API Testing

## API
JSONPlaceholder — https://jsonplaceholder.typicode.com

## Ажиллуулах заавар
1. Newman суулгах: `npm install -g newman newman-reporter-htmlextra`
2. Тест ажиллуулах: `newman run postman/collection.json -e postman/env.dev.json`
3. HTML report: `newman run postman/collection.json -e postman/env.dev.json --reporters cli,htmlextra --reporter-htmlextra-export reports/api.html`