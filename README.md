# notes-301-08.md
### Mongoose Populate
<p>Reminds me of a join on SQL...but way better. You link together different schema or documents with IDs.(but doesn't need to ID) Also You can check a value with populated() (and with depopulate() you remove the populated value)</p>

#### Express Routing 
<p>Express is middleware and part of it's middleware is the Router. Router makes things like  basic routes with express.Router() possible. Also express.Router() can route with parameters. (Example: router.get('/resource:name')) For use of middleware it will be router.use(themiddleware). app.routes creates routes with authentication/and shortcuts. Basically there are many tools that express can do with it's middleware.</p>

#### Populate Virtuals
<p>Let's you add "match" options. It relies on JSON.stringify() and needs <i>virtuals: true</i> for option to work. Also a "foeignField" is needed.</p>
