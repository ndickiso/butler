# butler

Examples and documentation for Trello's Butler allowing you to automate your workflow in plain English

## Getting Started

These are several light weight (a.k.a *wildwest*- no builds, test, tools, or folders for quick plug and play (: ), single page examples of how you could use Trello's Butler. Each example will have a unique Trello link that you will have to generate on your own. (https://bot.trellobutler.com/scripts/XXXXXXX)

Each example will have the corresponding screen shot of what the title of your Trello card should be, in your Butler list on a Trello board of your choice.  Make sure to setup your Trello Board with Butler before you try any examples. See *Setup Butler on Trello Board* below.

Once each unique URL is setup, you will need to create a simple json key value pair in a config.json at root of this folder. See *Configuration* below

The Examples will take advantage of programming helper libraries such as Jquery, Underscore & Bootstrap, but referencing a CDN to keep things light weight.

### Configuration

Make sure that you create a simple config.json file at root of this directory. This file will hold the unique Trello Butler URLs in key value pairs. Your data should something like this. *NOTE you must reference the correct key name that you assign for each example- i.e. "helloworld": for the creat-hello-world-card.html.*

```
{
  "helloworld" :  "https://bot.trellobutler.com/scripts/XXXXXXX"
  ...
}
```

Due to CORS Restrictions, you will need to serve up each example to read in your config.json file. I reccomend using something simple like node's [http-server](https://www.npmjs.com/package/http-server). In which you would run the following code in a terminal, then navigate to the desired example in your local host browser path.

Once in this *butler/* directory:

```
$ http-server .
```

Then navigate to *http://127.0.0.1:8080* and click on your desired example.

### Prerequisites

* Trello Account (with Butler invited to board, see below)



### Resources

[Butler Documentation](https://trello.com/b/2dLsEE9t/butler-for-trello) - A Trello Board to understand more about Trello, from the team that manages the project.


```
Give examples
```

### Setup Butler on Trello Board


To use Butler in a board, you just need to invite the user "butlerbot" to the board. Step by step:

* Open the board's menu by clicking in the **Show Menu** link in the upper right corner (If it's not already open).
* In the menu, click on **Add Members...**
* A member search box will appear. Type **butlerbot** in the search box.
* Click on **Butler Bot (butlerbot)** once it appears.


## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Bootstrap](https://v4-alpha.getbootstrap.com/) - The web framework used
* [Underscore.js](http://underscorejs.org/) - Functional Programming Library
* [JQuery](http://jquery.com/) - Obviously


## Authors

* **Nate Dickison** - *Initial work* - [FWS,inc.](http:faithworks.io)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
