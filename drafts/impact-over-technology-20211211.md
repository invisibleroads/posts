# Impact Over Technology 20211211

I spent much of the day agonizing over understanding the new ASGI frameworks such as [fastapi](https://github.com/tiangolo/fastapi), [quart](https://gitlab.com/pgjones/quart), [blacksheep](https://github.com/Neoteroi/BlackSheep). And the conclusion is that it is not so much the technology that matters but the impact. You can be in an infinite loop optimizing but if nobody uses your service, then you are not having any impact. We need to focus on impact.

A lot of the agonizing was over the thought that I had spent 10+ years developing various software that are no longer compatible with the latest technologies. And I was particularly paralyzed by the thought that I would have to relearn how to do various stuff with the latest technologies when I already know how to implement the same functionality using frameworks that I already know.

I decided that we can still re-use a lot of our legacy technology. Just because you have a computer does not mean you cannot still use a pen and paper notebook. Every technology has its advantages and disadvantages and there are cases where an ancient technology can be superior to a newfangled one.

To return to the case of the new ASGI frameworks, I think their use is most appreciated when one wants to serve asynchronous protocols such as websockets and server sent events entirely within the same script without having to rely on external services like redis or custom nodejs proxies. And these asynchronous protocols are more needed in rapid interactive  applications like online games and immersive experiences. For the use case of a marketplace or report, the WSGI frameworks work perfectly fine.

We can focus on the traditional business metrics of users and revenue. There are a lot of proxies for measuring impact.

As an engineer, I am constantly tempted to use the latest technologies, optimize the code and add more features. However, it is important to remind myself to focus on impact over technology.
