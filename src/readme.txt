npm init -y
npm install @wordpress/scripts

console cmd
> wp.data.select("core").getEntityRecords("postType","professor",{per_page: -1})