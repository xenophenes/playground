# Top of page

- pgEdge, Inc.

> **Bringing active-active replication, low latency, and zero downtime operations to PostgreSQL on-premises or in the cloud with 100% compatibility and no vendor lock-in.**

- (verified)
- https://pgedge.com
- support@pgedge.com

# README.md

[![github_banner](https://github.com/user-attachments/assets/0c34642a-bd3b-459a-8926-275233d12176)](https://www.pgedge.com/get-started/platform)

<div align="center">
  <a href="https://www.pgedge.com">Learn more</a> • 
  <a href="https://docs.pgedge.com">Docs</a> • 
  <a href="https://discord.com/invite/pgedge/login">Discord</a>
</div>

##

pgEdge delivers active-active PostgreSQL solutions for maximum high availability, ultra-low latency, zero downtime maintenance, and fault-tolerant systems across deployment options and cloud regions. Proudly [100% PostgreSQL compliant](https://pgscorecard.com/) and fully source-available, we're here to help you enable distributed Postgres no matter where your clusters are. 

## What's at our core

- [100% pure PostgreSQL](https://postgresql.org)
- [Spock, for enabling active-active replication with appropriate conflict resolution](https://github.com/pgEdge/spock)

## Download & install

We have a variety of download options available to make it quick and easy to start using pgEdge.

- [Sign up for pgEdge Cloud](https://www.pgedge.com/get-started/cloud) and get the first 30 days free.
- [Experience self-hosted pgEdge in 30 seconds](https://www.pgedge.com/get-started/containers) when deploying using containers. No license or feature restrictions for local use.
- [Self-host on VMs](www.pgedge.com/get-started/platform) with a free download license for unlimited development and evaluation, plus limited production usage (up to 4 vCPUs). 
- Prefer to work from the command line? For self-hosted pgEdge installations, take a look at our [command-line interface](https://github.com/pgEdge/cli).

### Integrations

- Install using a [Helm chart](https://github.com/pgEdge/pgedge-helm) to deploy quickly on Kubernetes.
- Explore [Dockerfile and Docker examples for pgEdge](https://github.com/pgEdge/pgedge-docker).
- [Connect Cloudflare Workers to your pgEdge database](https://github.com/pgEdge/cloudflare-worker-template) using our template.
- Working with [Terraform](https://github.com/pgEdge/terraform-provider-pgedge)? Our provider works seamlessly for both the Developer and Enterprise editions.
- Simplify the management of pgEdge Cloud resources using infrastructure as code with the [official Pulumi provider for pgEdge Cloud](https://github.com/pgEdge/pulumi-pgedge).
- [Leverage Patroni with pgEdge](https://github.com/pgEdge/pgedge-patroni) using pgedge-patroni.
- [Prefer using Ansible to deploy infrastructure and cluster resources?](https://github.com/pgEdge/pgedge-ansible) This collection will build a full pgEdge cluster for you.

## Get started

Self-hosting pgEdge? [Find the installation instructions here.](docs.pgedge.com/platform/installing_pgedge) 
_TODO: note any licensing restrictions here, and link to them._

Or, thinking of deploying in the cloud? [Learn more about pgEdge Cloud deployments here.](https://docs.pgedge.com/cloud)

## Developer resources

- [Blog](https://www.pgedge.com/blog)
- [FAQ](https://www.pgedge.com/resources/faq)
- [Demos](https://www.pgedge.com/demo-video)
- [YouTube](https://www.youtube.com/@pgEdge)

## Contact us, anytime

We provide [24/7 customer service](https://www.pgedge.com/support) for customers with thanks to our amazing team of experts, that includes contributors to the PostgreSQL ecosystem. 

If you have any specific questions about pgEdge in general, you can always [get in touch](https://www.pgedge.com/contact) and we're happy to help.

Otherwise, for technical questions, we're active on [Discord](https://discord.com/invite/pgedge/login) and are happy to help answer any queries there.

_Follow us on social_:

- [LinkedIn](https://www.linkedin.com/company/pgedge/)
- [Mastodon](https://mastodon.social/@pgEdgeDistributedPostgres)
- [Discord](https://discord.com/invite/pgedge/login)
- [X](https://twitter.com/pgEdgeInc)

# Pinned

1) https://github.com/pgEdge/spock 

     _Note: The description here should be updated to "Logical active-active PostgreSQL replication". The community is pretty good about staying away from "master" as a descriptor these days; it would be good to migrate over to "active-active" as a result. Additionally, it's not immediately clear from the preview that this is a PostgreSQL extension, and it should be._

2) https://github.com/pgEdge/cli
   
     _Note: This is a valuable tool for pgEdge users - it should be highlighted as the second link here as a result. For the description, is this a tool only for pgEdge Platform? What about pgEdge Cloud? Recommend rephrasing to something like "Command line interface for pgEdge Platform and pgEdge Cloud" (as applicable)._

3) https://github.com/pgEdge/snowflake

     _Note: "Snowflake Sequences for PostgreSQL" in the description here should be replaced with something more descriptive, i.e. "Unique PostgreSQL sequence values for use in active-active clusters" or something similar. "Snowflake" here can be easily confused for "SnowflakeDB" particularly after their acquisition of Crunchy Data._

5) https://github.com/pgEdge/lolor

     _Note: Similarly to the first item here, this description should be updated to "PostgreSQL Large Object LOgical Replication (LOLOR)". Maybe it's just me, but I definitely thought "LOgical" was a typo at first so it would be nice to point out that's the written out version of "lolor" - and, again, the fact that this is a PostgreSQL extension should be highlighted._

# Other thoughts

Once this page is live, let's do a whole social promo for it to drive followers of the pgEdge account.

1) What other repositories are planned, if any? Can we talk about anything that might be "coming soon" to drive followers?
