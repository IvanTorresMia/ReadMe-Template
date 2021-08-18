# Portfolio

## Table of Contents

- [Description](#Description)
- [Deployed Link](#Deployed-Link)
- [Technologies](#Technologies)
- [Code](#Code)
- [Gif](#Gif)
- [Author](#Author)
- [Credits](#Credits)
- [License](#License)

## Description

Hello! Welcome to my portfolio! Here you will find more about me and the work that I have done in the past enjoy!

## Deployed-Link
<!-- add deployed link in the paranthesis -->
- [Click Here]()

## Technologies
<!-- left examples here put edit to put your technologies -->
- [JavaScript](https://www.w3schools.com/js/)
- [AOS](https://michalsnik.github.io/aos/)
- [ReactJs](https://reactjs.org/)


## Gif
<!-- path to gif in paranthesis  -->
![Gif]()

## Code

### Technology name that you want to show off

- Description

* Installation if required

```
Code snippet
```


<!-- Example of the obove -->
### Material-UI

* Material UI was a new technology for me, so implementing it to my portfolio exciting

- installation

```
npm install @material-ui/core
```

- Importing different components and styles from materia-ui

```
import { makeStyles } from '@material-ui/core/styles';
import Card from '@material-ui/core/Card';
import CardActionArea from '@material-ui/core/CardActionArea';
import CardActions from '@material-ui/core/CardActions';
import CardContent from '@material-ui/core/CardContent';
import CardMedia from '@material-ui/core/CardMedia';
import Typography from '@material-ui/core/Typography';
```

- using styles

```
const useStyles = makeStyles({
  root: {
    maxWidth: 395,
    margin: "2rem",
    textAlign: "center",
    backgroundColor: "rgb(76, 76, 76)",
    color: "#fff"
  },
  media: {
    height: 140,
  },
});
```

- example card

```
// Once Imported you can start using the components and styles from material-ui

 <div className="col-sm-4 card-container">
      <Card className={classes.root}>
        <CardActionArea>
          <CardMedia
            className={classes.media}
            image={Projects.img}
            title="Contemplative Reptile"
          />
          <CardContent>
            <Typography gutterBottom variant="h5" component="h2">
              {Projects.name}
            </Typography>
            <Typography
              variant="body2"
              color="textSecondary"
              component="p"
              className="card-p"
            >
              {Projects.discription}
            </Typography>
          </CardContent>
        </CardActionArea>
        <CardActions>
          <a href={Projects.github} target="_blank" rel="noreferrer">
            <img
              className="img-thumbnail m-2"
              src={githubLogo}
              alt="GitHub Icon"
            />
          </a>
          <a href={Projects.Deployed} target="_blank" rel="noreferrer">
            <img
              className="img-thumbnail m-2"
              src={deployedLogo}
              alt="GitHub Icon"
            />
          </a>
        </CardActions>
      </Card>
    </div>
```

## Author

Your name

<!-- add linnks to your social media -->
- [GitHub]()
- [linkedIn]()

## Credits

- add credits here
- [StackOverFlow](https://stackoverflow.com/)

## License]

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://www.mit.edu/~amini/LICENSE.md)
