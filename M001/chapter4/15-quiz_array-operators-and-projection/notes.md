db.companies.find({ "funding_rounds": { "$size": 8 } },
                  { "name": 1, "_id": 0 })

This is correct.

Since we are looking to only view the names of companies then we have to explicitly exclude the _id in the projection.
