# Browser Specific Code
While working with animations, I figured out that Safari does not support smooth scroll and FireFox has glitches rendering the snowfall. So I needed browser specific behavior and ended up creating a react component that renders code for specific browsers.

You can find the code for the component here — Browser Component. I’m thinking about writing thorough test cases and open-sourcing this component sometime soon.

It’s pretty neat to use the component like this.
```
<Browser except firefox chrome mobile>
  <span>All the magic tricks in this site work best in 
    <b>Chrome!</b>
  </span>
</Browser>
<Browser only firefox>
  <span>Magic background is disabled in FireFox. Try in 
    <b>Chrome!</b>
  </span>
</Browser>
```
[source here](https://codeburst.io/i-created-my-portfolio-with-react-and-some-magic-fe661302ce4c)
## License

MIT © Dinesh Pandiyan