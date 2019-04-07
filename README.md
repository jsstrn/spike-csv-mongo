# spike-csv-mongo

This spike tries to upload `csv` files in MongoDB

## Checklist

- [x] Upload any file to a destination folder `public/uploads`
- [ ] Save any file as Buffer object to the database
- [ ] Only save `csv` files to the database

## Notes

- MongoDB can store files as Buffer objects if they are less than 16MB
- For file sizes larger than 16MB, use [GridFS](https://docs.mongodb.com/manual/core/gridfs/)
- Our `csv` files are unlikely to be greater than 16MB
