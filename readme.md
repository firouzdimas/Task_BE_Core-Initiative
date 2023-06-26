# Self payroll system
The main feature of this web service is that employees can withdraw salaries independently every month.

Further details, the features that must be done are:

1. Manage position data in the form of CRUD operations (create, read, update, delete)
2. Manage employee data in the form of CRUD operations (Create, Read, Update, Delete)
3. Admin can topup company balance
4. Withdraw sallary by including employee ID and secret ID, the amount of salary is based on the position held by each employee.
5. There is a history of topup and reduction of company balance 

## Features

The following features are included in the system:

1. Position Management: CRUD operations (Create, Read, Update, Delete) to manage position data.
2. Employee Management: CRUD operations (Create, Read, Update, Delete) to manage employee data.
3. Admin Balance Top-up: Admin can top up the company balance.
4. Salary Withdrawals: Employees can withdraw their salaries by providing their Employee ID and Secret ID. The salary amount is based on the position held by each employee.
5. Transaction History: Transaction history of top-ups and reductions of the company's balance.

## Tools

The following tools were used to build this project:

- [Echo Framework](https://github.com/labstack/echo)
- [PostgreSQL](https://www.postgresql.org/) as database
- [GORM](https://gorm.io/) as ORM
- [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) as input validation

## Getting Started

To run the application, follow the instructions below:

1. Clone this repository and navigate to the project directory.

   ```bash
   git clone https://github.com/szczynk/self-payroll.git
   ```

1. Create a `.env` file by running `cp .env.example .env`. Then fill in the `.env` file according to your local environment.

   ```bash
   cp .env.example .env
   ```

1. Run `go mod tidy && go mod vendor`.

   ```bash
   go mod tidy && go mod vendor
   ```

1. Run `go run *.go`.

   ```bash
   go run *.go
   ```

The list of endpoints is available in the [documenter](https://documenter.getpostman.com/view/4080490/2s83Ychhk4).

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for 
