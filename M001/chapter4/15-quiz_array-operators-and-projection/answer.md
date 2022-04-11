db.companies.find({ "funding_rounds": { "$size": 8 } },
                  { "name": 1, "_id": 0 })
