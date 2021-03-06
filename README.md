# layering-profile-images
If you need to show a list of users, members, or anything similar, you may want to display profile images over one another to both conserve space and create a feeling grouping amongst those users.

## Tutorial
For detailed instruction's, view Solodev's [How to Layer Profile Images Over One Another](https://www.solodev.com/blog/web-design/how-to-layer-profile-images-over-one-another.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/fxd54L8s/3/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="col-sm-9 col-xl-10 order-2 order-sm-1">
      <div id="grid_groups_wrapper" class="">
        <table id="grid_groups" class="table table-hover w-100" role="grid">
          <thead>
            <tr role="row">
              <th class="user_group_image_id grid-icon sorting_asc" rowspan="1" colspan="1" style="width: 25px;"></th>
              <th class="name sorting" tabindex="0" aria-controls="grid_groups" rowspan="1" colspan="1"
                   style="width: 100px;">
                Group Name
              </th>
              <th class="members" rowspan="1" colspan="1" aria-label="Members" style="width: 445px;">
                Members
              </th>
            </tr>
          </thead>
          <tbody>
            <tr role="row group" class="odd">
              <td class="grid-icon">
                <div class="default-avatar rounded-circle d-flex align-items-center justify-content-center mx-auto text-uppercase">A</div>
              </td>
              <td class="group-class">Administrators</td>
              <td><a class="route d-flex">
                  <div title="Baby Yoda" class="rounded-circle default-avatar member-overlap-item" 
                       style="background: url(https://raw.githubusercontent.com/solodev/layering-profile-images/master/images/baby-yoda.jpg) 0 0 no-repeat; background-size: cover;">
                  </div>
                  <div title="R2D2" class="rounded-circle default-avatar member-overlap-item"
                       style="background: url(https://raw.githubusercontent.com/solodev/layering-profile-images/master/images/r2d2.jpg) 0 0 no-repeat; background-size: cover;">
                  </div>
                  <div title="Jabba the Hut" class="rounded-circle default-avatar member-overlap-item"
                       style="background: url(https://raw.githubusercontent.com/solodev/layering-profile-images/master/images/jabba-the-hut.png) 0 0 no-repeat; background-size: cover;">
                  </div>
                  <div title="Chewbacca" class="rounded-circle default-avatar member-overlap-item"
                       style="background: url(https://raw.githubusercontent.com/solodev/layering-profile-images/master/images/chewy.png) 0 0 no-repeat; background-size: cover;">
                  </div>
                  <div title="C-3PO" class="rounded-circle default-avatar member-overlap-item"
                       style="background: url(https://raw.githubusercontent.com/solodev/layering-profile-images/master/images/c-3po.jpg) 0 0 no-repeat; background-size: cover;">
                  </div>
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
 <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
```