#forecrawl

Forecrawl is an autononomous online search agent framework that endeavors to more efficiently crawl the web. By combining uninformed and heuristic search strategies with state-of-the-art techniques in machine learning, forecrawl aspires to become the most efficient goal- and utility-driven web crawler.

## Overview

At its core, forecrawl is a WebKit2 port. In choosing its next action to perform, forecrawl considers the DOM, render, and layout tress that WebCore provides in addition to how the web site's content appears at different screen resolutions. Whether forecrawl decides to click a link or enter text into an input field, forecrawl will only use the WebCore HTML editing and keyboard handling functions. This protocol ensures that forecrawl's actions will appear as organic as possible.

As forecrawl operates, users may view its progress at each decision point or state transition. Users can indicate whether forecrawl acted optimally or sub-optimally, and if necessary, provide the optimal response. Forecrawl will learn from this feedback as it continues its task.

The last major component is that forecrawl aims to act in a multiagent setting by receiving feedback from other forecrawl instances; in this sense, one can view forecrawl as a multi-agent system that learns from the experience of other instances in its cluster.

## Status

This project was conceived on 8 January 2013, and is in the brainstorming phases. If you would like to contribute or have any questions, please feel free to join #forecrawl on Freenode.
