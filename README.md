# 什么是iLogtail



iLogtail 为可观测场景而生，拥有的轻量级、高性能、自动化配置等诸多生产级别特性，在阿里巴巴以及外部数万家阿里云客户内部广泛应用。你可以将它部署于物理机，虚拟机，Kubernetes等多种环境中来采集遥测数据，例如logs、traces和metrics。

**iLogtail** 的核心优势主要有：

* 支持多种Logs、Traces、Metrics数据采集，尤其对容器、Kubernetes环境支持非常友好
* 数据采集资源消耗极低，相比同类遥测数据采集的Agent性能好5-20倍
* 高稳定性，在阿里巴巴以及数万阿里云客户生产中使用验证，部署量近千万，每天采集数十PB可观测数据
* 支持插件化扩展，可任意扩充数据采集、处理、聚合、发送模块
* 支持配置远程管理，支持以图形化、SDK、K8s Operator等方式进行配置管理，可轻松管理百万台机器的数据采集
* 支持自监控、流量控制、资源控制、主动告警、采集统计等多种高级特性

**iLogtail** 支持收集多种遥测数据并将其传输到多种不同的后端，例如 [SLS可观测平台](https://help.aliyun.com/product/28958.html) 。 支持采集的数据主要如下:

* Logs
  * 收集静态日志文件
  * 在容器化环境中运行时动态收集文件
  * 在容器化环境中运行时动态收集 Stdout
* Traces
  * OpenTelemetry 协议
  * Skywalking V2 协议
  * Skywalking V3 协议
  * ...
* Metrics
  * Node指标
  * Process指标
  * GPU 指标
  * Nginx 指标
  * 支持获取Prometheus指标
  * 支持收集Telegraf指标
  * ...

{% hint style="info" %}
**Good to know:** providing a brief overview of your product and its core use cases is a great place to start with product docs. Your product might seem obvious to you – you made it! However, to others, even folks who are trying your product after reading your site or getting a sales demo, it can still be unclear. This is your chance to clarify your product and set the right expectations!
{% endhint %}

> Loom is a video messaging tool that helps you get your message across through instantly shareable videos.
>
> With Loom, you can record your camera, microphone, and desktop simultaneously. Your video is then instantly available to share through Loom's patented technology.
>
> — From the [Loom Docs](https://support.loom.com/hc/en-us/articles/360002158057-What-is-Loom-)

> The Mailchimp Marketing API provides programmatic access to Mailchimp data and functionality, allowing developers to build custom features to do things like sync email activity and campaign analytics with their database, manage audiences and campaigns, and more.
>
> — From the [Mailchimp Marketing API docs](https://mailchimp.com/developer/marketing/docs/fundamentals/)

## Getting Started

**Got 2 minutes?** Check out a video overview of our product:

{% embed url="https://www.loom.com/share/3bfa83acc9fd41b7b98b803ba9197d90" %}

{% hint style="info" %}
**Good to know:** A succinct video overview is a great way to introduce folks to your product. Embed a Loom, Vimeo or YouTube video and you're good to go! We love this video from the fine folks at [Loom](https://loom.com) as a perfect example of a succinct feature overview.
{% endhint %}

### Guides: Jump right in

Follow our handy guides to get started on the basics as quickly as possible:

{% content-ref url="guides/creating-your-first-project.md" %}
[creating-your-first-project.md](guides/creating-your-first-project.md)
{% endcontent-ref %}

{% content-ref url="guides/creating-your-first-task.md" %}
[creating-your-first-task.md](guides/creating-your-first-task.md)
{% endcontent-ref %}

{% content-ref url="guides/advanced-permissions.md" %}
[advanced-permissions.md](guides/advanced-permissions.md)
{% endcontent-ref %}

{% hint style="info" %}
**Good to know:** your product docs aren't just a reference of all your features! use them to encourage folks to perform certain actions and discover the value in your product.
{% endhint %}

### Fundamentals: Dive a little deeper

Learn the fundamentals of MyProduct to get a deeper understanding of our main features:

{% content-ref url="fundamentals/projects.md" %}
[projects.md](fundamentals/projects.md)
{% endcontent-ref %}

{% content-ref url="fundamentals/members.md" %}
[members.md](fundamentals/members.md)
{% endcontent-ref %}

{% content-ref url="fundamentals/task-lists.md" %}
[task-lists.md](fundamentals/task-lists.md)
{% endcontent-ref %}

{% content-ref url="fundamentals/tasks.md" %}
[tasks.md](fundamentals/tasks.md)
{% endcontent-ref %}

{% hint style="info" %}
**Good to know:** Splitting your product into fundamental concepts, objects, or areas can be a great way to let readers deep dive into the concepts that matter most to them. Combine guides with this approach to 'fundamentals' and you're well on your way to great documentation!
{% endhint %}
