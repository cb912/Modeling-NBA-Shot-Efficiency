# Modeling Shot Efficiency in the NBA

[Project](https://sta210-fa20.netlify.app/project/) for STA 210, Fall 2020

Our project conducts a thorough analysis of game data from the 2014-2015 season of the National Basketball Association (NBA) using a variety of statistical methods, and investiages a series of factors which ultimately determine whether or not a shot is made into a basket. Based on our analysis and model output, we found that a shot closer to the basket and further away from the closest defender is expected to be a successful shot. We conclude that shot distance, distance to closest defender, and time left on the clock are the three most significant predictors, which aligned with our initial hypothesis.

The response variable we are interested in investigating is:

- `SHOT_SUCCESS`: Indicates whether or not the NBA player scored the shot. `SHOT_SUCCESS` takes a value of 1 if the shot was made, 0 otherwise.

The predictor variables that we expect to have an influence on the response variable are:

- `SHOT_CLOCK`: Number of seconds left on the shot clock when the player shot the ball.
- `SHOT_DIST`: Distance in feet from the hoop when the player shot the ball.
- `SHOT_RESULT`: Description of shot, either "made" or "missed".
- `TOUCH_TIME`: Number of seconds before the player shot the ball after being passed to.
- `CLOSEST_DEFENDER`: Who the closest defender was to the shooting player.
- `CLOSE_DEF_DIST`: Number of feet the defender was from the player when the ball was shot.
- `Player_name`: Name of player who shot the ball.